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
  - summary: Prohibited call types
    text: Don't use CallSimple for sales or marketing calls, debt collection, threats, harassment, pretending to be someone else, or getting OTPs, passwords or bank details.
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
name: CallSimple
provenance_date: '2026-11-09'
provider_name: CallSimple
provider_slug: callsimple-app
slug: callsimple-app-eligibility
source_date: '2026-11-09'
source_filename: callsimple-app-eligibility.yml
source_heading: Eligibility
source_page: https://callsimple.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CallSimple\naid: callsimple-app\nurl: https://callsimple.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited call types\n  text: Don't use CallSimple for sales or marketing calls, debt collection, threats, harassment, pretending to be\n    someone else, or getting OTPs, passwords or bank details.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/callsimple-app/eligibility/callsimple-app-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from CallSimple's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Voice Agents
- Phone Calls
- MCP
- ChatGPT Apps
- Claude Connectors
- Voice
- India
---
