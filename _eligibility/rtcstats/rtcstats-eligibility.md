---
api_specs:
- filename: rtcstats-rtcstats-api-api-openapi.yml
  format: yaml
  label: rtcStats API
  slug: rtcstats-rtcstats-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rtcstats/openapi/rtcstats-rtcstats-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a human.
    type: individual
  - text: When we say "You" or "your", we are referring to the people or organizations that have an account on rtcstats.com.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Analyzing own WebRTC statistics only
    text: You may use the Services for the purpose of analyzing WebRTC statistics of your service and nothing else.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Accounts registered by "bots" or other automated methods are not permitted.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: rtcStats
provenance_date: '2026-11-10'
provider_name: rtcStats
provider_slug: rtcstats
slug: rtcstats-eligibility
source_date: '2026-11-10'
source_filename: rtcstats-eligibility.yml
source_heading: Eligibility
source_page: https://rtcstats.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rtcStats\naid: rtcstats\nurl: https://rtcstats.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a human.\n- type: business\n  text: When we say \"You\" or \"your\", we are referring to the people or organizations that have an account on rtcstats.com.\nrestricted_uses:\n- summary: Analyzing own WebRTC statistics only\n  text: You may use the Services for the purpose of analyzing WebRTC statistics of your service and nothing else.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Accounts\
  \ registered by \"bots\" or other automated methods are not permitted.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rtcstats/eligibility/rtcstats-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from rtcStats's own page on 2026-11-10.
synthetic: false
tags:
- WebRTC
- Observability
- Monitoring
- Debugging
- Real-Time Communication
- Video
- Voice
- Artificial Intelligence
- MCP
- Developer Tools
---
