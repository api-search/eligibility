---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Export clause prohibits use or export to OFAC/EU sanctioned countries including Burma, Cuba, Iran, Libya, Sudan, Syria and North Korea.
  entity_types:
  - text: This provision applies only if You are the United States Government or a state or local government entity located in the United States
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No use by direct competitors
    text: (iv) license or purchase the Services if You are a direct competitor (or an agent of a direct competitor) of Devo
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
name: Devo
provenance_date: '2026-11-09'
provider_name: Devo
provider_slug: devo
slug: devo-eligibility
source_date: '2026-11-09'
source_filename: devo-eligibility.yml
source_heading: Eligibility
source_page: https://www.devo.com/legal-hub/devo-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Devo\naid: devo\nurl: https://www.devo.com/legal-hub/devo-terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Export clause prohibits use or export to OFAC/EU sanctioned countries including Burma, Cuba, Iran, Libya,\n    Sudan, Syria and North Korea.\nentity_types:\n- type: government\n  text: This provision applies only if You are the United States Government or a state or local government entity\n    located in the United States\nrestricted_uses:\n- summary: No use by direct competitors\n  text: (iv) license or purchase the Services if You are a direct competitor\
  \ (or an agent of a direct competitor)\n    of Devo\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/devo/eligibility/devo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Devo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cybersecurity
- SIEM
- Security
- Security Data Platform
- Threat Detection
- Log Management
- Analytics
- Observability
- Query API
---
