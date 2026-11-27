---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are at least 18 and have authority to bind any organization you represent.
    type: individual
  - text: have authority to bind any organization you represent
    type: business
  minimum_age:
    text: You are at least 18
    value: '18'
  restricted_uses:
  - summary: High-risk contexts
    text: use Vela in high-risk contexts where errors could cause harm (e.g., medical decisions, emergency services)
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
name: Vela
provenance_date: '2026-11-10'
provider_name: Vela
provider_slug: vela
slug: vela-eligibility
source_date: '2026-11-10'
source_filename: vela-eligibility.yml
source_heading: Eligibility
source_page: https://tryvela.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vela\naid: vela\nurl: https://tryvela.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are at least 18 and have authority to bind any organization you represent.\n- type: business\n  text: have authority to bind any organization you represent\nrestricted_uses:\n- summary: High-risk contexts\n  text: use Vela in high-risk contexts where errors could cause harm (e.g., medical decisions, emergency services)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text:\
  \ You are at least 18\n"
source_yaml_url: https://artifacts.apis.io/vela/eligibility/vela-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Vela's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Scheduling
- Artificial Intelligence
- AI Agents
- Meetings
- Calendar
- Recruiting
- Productivity
---
