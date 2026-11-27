---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No emergency calls
    text: /call-me is not a telephone service and must not be used for emergency calls.
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
name: /call-me
provenance_date: '2026-11-09'
provider_name: /call-me
provider_slug: callmemcp-com
slug: callmemcp-com-eligibility
source_date: '2026-11-09'
source_filename: callmemcp-com-eligibility.yml
source_heading: Eligibility
source_page: https://callmemcp.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: /call-me\naid: callmemcp-com\nurl: https://callmemcp.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No emergency calls\n  text: /call-me is not a telephone service and must not be used for emergency calls.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/callmemcp-com/eligibility/callmemcp-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from /call-me's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- AI Agents
- Voice
- Phone Calls
- Notification
- Mobile
- Developer Tools
---
