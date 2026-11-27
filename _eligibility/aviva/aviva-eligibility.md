---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: los servicios brindados en la App, sólo están disponibles para Clientes de Avvia que tengan capacidad legal para contratar
    type: individual
  minimum_age:
    text: No podrán utilizar los servicios las personas que no tengan esa característica, los menores de edad
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Aviva
provenance_date: '2026-11-09'
provider_name: Aviva
provider_slug: aviva
slug: aviva-eligibility
source_date: '2026-11-09'
source_filename: aviva-eligibility.yml
source_heading: Eligibility
source_page: https://www.avivacredito.com/terminos-y-condiciones/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aviva\naid: aviva\nurl: https://www.avivacredito.com/terminos-y-condiciones/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: los servicios brindados en la App, sólo están disponibles para Clientes de Avvia que tengan capacidad legal\n    para contratar\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: No podrán utilizar los servicios las personas que no tengan esa característica, los menores de edad\n"
source_yaml_url: https://artifacts.apis.io/aviva/eligibility/aviva-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Aviva's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Lending
- Consumer Credit
- Loans
- SOFOM
- Mexico
---
