---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: you represent that you are not a resident of Cuba, Iran, North Korea, Sudan or Syria.
  entity_types:
  - text: If you are entering into this EULA on behalf of an entity (such as a company, firm, partnership, or any other organization type), you are agreeing to bind that entity to this EULA
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No competing use of Service information
    text: you will not use the information derived from the Service or other information obtained from us to compete against Cargado in any way
  - summary: No double-brokering or intermediary insertion
    text: (ii) double-brokering freight or trucks; (iii) inserting an intermediary in transactions on the Service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cargado
provenance_date: '2026-11-09'
provider_name: Cargado
provider_slug: cargado
slug: cargado-eligibility
source_date: '2026-11-09'
source_filename: cargado-eligibility.yml
source_heading: Eligibility
source_page: https://cargado.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cargado\naid: cargado\nurl: https://cargado.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: you represent that you are not a resident of Cuba, Iran, North Korea, Sudan or Syria.\nentity_types:\n- type: business\n  text: If you are entering into this EULA on behalf of an entity (such as a company, firm, partnership, or any\n    other organization type), you are agreeing to bind that entity to this EULA\nrestricted_uses:\n- summary: No competing use of Service information\n  text: you will not use the information derived\
  \ from the Service or other information obtained from us to compete\n    against Cargado in any way\n- summary: No double-brokering or intermediary insertion\n  text: (ii) double-brokering freight or trucks; (iii) inserting an intermediary in transactions on the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cargado/eligibility/cargado-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Cargado's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Freight
- Marketplace
- Logistics
---
