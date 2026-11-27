---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: gestionando una base de datos de personas demandantes de empleo que voluntariamente deseen formar parte de la misma
    type: individual
  - text: Las empresas que publiquen ofertas de empleo en el Portal autorizan a Incluyeme en forma expresa y gratuita
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Actividades ilícitas o contrarias a la ley
    text: El Usuario se obliga a abstenerse de utilizar el Portal y los Servicios con fines o efectos ilícitos
  verification:
    approval_required: true
    kyb: null
    kyc: false
    text: Incluyeme tampoco tiene la obligación de verificar y no verifica la identidad de los Usuarios
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Incluyeme
provenance_date: '2026-11-09'
provider_name: Incluyeme
provider_slug: incluyeme
slug: incluyeme-eligibility
source_date: '2026-11-09'
source_filename: incluyeme-eligibility.yml
source_heading: Eligibility
source_page: https://www.incluyeme.com/terminos-y-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Incluyeme\naid: incluyeme\nurl: https://www.incluyeme.com/terminos-y-condiciones/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: gestionando una base de datos de personas demandantes de empleo que voluntariamente deseen formar parte\n    de la misma\n- type: business\n  text: Las empresas que publiquen ofertas de empleo en el Portal autorizan a Incluyeme en forma expresa y gratuita\nrestricted_uses:\n- summary: Actividades ilícitas o contrarias a la ley\n  text: El Usuario se obliga a abstenerse de utilizar el Portal y los Servicios\
  \ con fines o efectos ilícitos\nverification:\n  kyc: false\n  kyb: null\n  approval_required: true\n  text: Incluyeme tampoco tiene la obligación de verificar y no verifica la identidad de los Usuarios\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/incluyeme/eligibility/incluyeme-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Incluyeme's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Disability Inclusion
- Employment
- Recruiting
- Job Board
- Human Resources
- Accessibility
- Diversity Equity and Inclusion
- Social Enterprise
- Latin America
- Training
---
