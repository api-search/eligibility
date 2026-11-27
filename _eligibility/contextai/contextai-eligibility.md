---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: use any Context IP for any activity where use or failure of the Context IP could lead to death, personal injury, or environmental damage, including life support systems, emergency services, nuclear facilities, autonomous vehicles, or air traffic control
  - summary: Sensitive Data
    text: Customer will not use the Services to store Sensitive Data
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
name: Context.ai *
provenance_date: '2026-11-09'
provider_name: Context.ai *
provider_slug: contextai
slug: contextai-eligibility
source_date: '2026-11-09'
source_filename: contextai-eligibility.yml
source_heading: Eligibility
source_page: https://www.context.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Context.ai *\naid: contextai\nurl: https://www.context.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement\nrestricted_uses:\n- summary: High-risk activities\n  text: use any Context IP for any activity where use or failure of the Context IP could lead to death, personal\n    injury, or environmental damage, including life support systems, emergency services, nuclear facilities, autonomous\n    vehicles, or air traffic control\n- summary: Sensitive\
  \ Data\n  text: Customer will not use the Services to store Sensitive Data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/contextai/eligibility/contextai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Context.ai *'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Enterprise AI
- Agent Platform
- LLM
- Automation
- Evaluation
---
