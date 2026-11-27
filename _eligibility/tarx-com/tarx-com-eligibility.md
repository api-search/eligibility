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
  - summary: Harmful or illegal use
    text: Use TARX to harm others, generate illegal content, harass people, or attack systems you do not own.
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
name: TARXAN
provenance_date: '2026-11-10'
provider_name: TARXAN
provider_slug: tarx-com
slug: tarx-com-eligibility
source_date: '2026-11-10'
source_filename: tarx-com-eligibility.yml
source_heading: Eligibility
source_page: https://tarx.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TARXAN\naid: tarx-com\nurl: https://tarx.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harmful or illegal use\n  text: Use TARX to harm others, generate illegal content, harass people, or attack systems you do not own.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tarx-com/eligibility/tarx-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from TARXAN's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Agent Runtime
- Local-First AI
- Private AI
- MCP
- A2A
- LLM
- Inference
- Developer Tools
- Hardware
- Robotics
---
