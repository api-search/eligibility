---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: El registro sólo está permitido para las personas físicas mayores de 18 años
    type: individual
  - text: personas morales
    type: business
  minimum_age:
    text: El registro sólo está permitido para las personas físicas mayores de 18 años
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Para el registro, le será solicitada su número telefónico, nombre, y correo electrónico.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cheaf
provenance_date: '2026-11-09'
provider_name: Cheaf
provider_slug: cheaf
slug: cheaf-eligibility
source_date: '2026-11-09'
source_filename: cheaf-eligibility.yml
source_heading: Eligibility
source_page: https://www.cheaf.com/terminos-y-condiciones
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cheaf\naid: cheaf\nurl: https://www.cheaf.com/terminos-y-condiciones\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: El registro sólo está permitido para las personas físicas mayores de 18 años\n- type: business\n  text: personas morales\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Para el registro, le será solicitada su número telefónico, nombre, y correo electrónico.\nminimum_age:\n  value: '18'\n  text: El registro sólo está permitido para las personas físicas mayores de 18 años\n"
source_yaml_url: https://artifacts.apis.io/cheaf/eligibility/cheaf-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Cheaf's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Tech
- Marketplace
- Food Waste
- Sustainability
- Retail
- Mobile App
- Latin America
---
