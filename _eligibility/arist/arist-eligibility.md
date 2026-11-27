---
claim_count: 3
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
    text: Company will not permit its Users to access or use the Services in a U.S. embargoed country (currently Cuba, Iran, North Korea, Sudan or Syria)
  entity_types:
  - text: the entity (“Company”) executing an order referencing this Agreement (“Order”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-controlled use
    text: Company represents that Company and its Users are not named on any U.S. government denied-party list.
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
name: Arist
provenance_date: '2026-11-09'
provider_name: Arist
provider_slug: arist
slug: arist-eligibility
source_date: '2026-11-09'
source_filename: arist-eligibility.yml
source_heading: Eligibility
source_page: https://arist.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arist\naid: arist\nurl: https://arist.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Company will not permit its Users to access or use the Services in a U.S. embargoed country (currently Cuba,\n    Iran, North Korea, Sudan or Syria)\nentity_types:\n- type: business\n  text: the entity (“Company”) executing an order referencing this Agreement (“Order”)\nrestricted_uses:\n- summary: Export-controlled use\n  text: Company represents that Company and its Users are not named on any U.S. government denied-party list.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/arist/eligibility/arist-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Arist's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Learning
- Training
- Enablement
- Microlearning
- Human Resources
- Messaging
- Artificial Intelligence
- Employee Communications
- Software-as-a-Service
---
