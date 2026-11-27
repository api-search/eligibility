---
api_specs:
- filename: uptybots-com-openapi-generated.yml
  format: yaml
  label: uptybots-com API
  slug: uptybots-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uptybots-com/openapi/_ae-authored/uptybots-com-openapi-generated.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - IR
    - KP
    - SY
    - CU
    - RU
    served: []
    text: 'you are not located in , not a resident of , and not accessing the Service from any country or region currently under comprehensive sanctions, including but not limited to: Iran North Korea Syria Cuba Russia'
  entity_types:
  - text: You are at least 18 years old or the legal age of majority in your jurisdiction.
    type: individual
  - text: '"User" - any individual or entity that accesses, registers, or uses the Service.'
    type: business
  minimum_age:
    text: You are at least 18 years old or the legal age of majority in your jurisdiction.
    value: '18'
  restricted_uses:
  - summary: Monitoring without permission
    text: You will not use the Service to monitor, scan, attack, or otherwise interfere with any systems or resources that you do not own or do not have explicit permission to monitor.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- KP
- SY
- CU
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: uptybots-com
provenance_date: '2026-11-10'
provider_name: uptybots-com
provider_slug: uptybots-com
slug: uptybots-com-eligibility
source_date: '2026-11-10'
source_filename: uptybots-com-eligibility.yml
source_heading: Eligibility
source_page: https://uptybots.com/page/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: uptybots-com\naid: uptybots-com\nurl: https://uptybots.com/page/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - KP\n  - SY\n  - CU\n  - RU\n  text: 'you are not located in , not a resident of , and not accessing the Service from any country or region currently\n    under comprehensive sanctions, including but not limited to: Iran North Korea Syria Cuba Russia'\nentity_types:\n- type: individual\n  text: You are at least 18 years old or the legal age of majority in your jurisdiction.\n- type: business\n  text: '\"User\" - any individual or entity that accesses, registers, or\
  \ uses the Service.'\nrestricted_uses:\n- summary: Monitoring without permission\n  text: You will not use the Service to monitor, scan, attack, or otherwise interfere with any systems or resources\n    that you do not own or do not have explicit permission to monitor.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old or the legal age of majority in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/uptybots-com/eligibility/uptybots-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from uptybots-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Monitoring
- Uptime
- Artificial Intelligence
- MCP
---
