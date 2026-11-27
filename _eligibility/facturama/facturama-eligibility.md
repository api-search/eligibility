---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'USUARIO (El Cliente): Es la persona que voluntariamente se registra en La Plataforma'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal use prohibited
    text: utilizar El Sitio para cualquier fin ilícito, en violación a las leyes, regulaciones, y disposiciones fiscales
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
name: Facturama
provenance_date: '2026-11-09'
provider_name: Facturama
provider_slug: facturama
slug: facturama-eligibility
source_date: '2026-11-09'
source_filename: facturama-eligibility.yml
source_heading: Eligibility
source_page: https://cdnfacturama.azureedge.net/content/docs/Facturama-terminos-y-condiciones-del-servicio.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Facturama\naid: facturama\nurl: https://cdnfacturama.azureedge.net/content/docs/Facturama-terminos-y-condiciones-del-servicio.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'USUARIO (El Cliente): Es la persona que voluntariamente se registra en La Plataforma'\nrestricted_uses:\n- summary: Illegal use prohibited\n  text: utilizar El Sitio para cualquier fin ilícito, en violación a las leyes, regulaciones, y disposiciones fiscales\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n \
  \ value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/facturama/eligibility/facturama-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Facturama's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Invoicing
- CFDI
- Mexico
- Tax Compliance
- SAT
- Billing
- Payroll
- Finance
- REST API
---
