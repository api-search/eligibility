---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Nefesh AI provides a B2B middleware API for real-time stress state estimation.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No clinical or safety-critical use
    text: 'The stress scores and wellness indicators produced by the API must NOT be used for: clinical decision-making, medical diagnoses, medication dosing or treatment decisions, emergency triage, or any safety-critical application.'
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
name: Nefesh AI
provenance_date: '2026-11-10'
provider_name: Nefesh AI
provider_slug: nefesh-ai
slug: nefesh-ai-eligibility
source_date: '2026-11-10'
source_filename: nefesh-ai-eligibility.yml
source_heading: Eligibility
source_page: https://nefesh.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nefesh AI\naid: nefesh-ai\nurl: https://nefesh.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Nefesh AI provides a B2B middleware API for real-time stress state estimation.\nrestricted_uses:\n- summary: No clinical or safety-critical use\n  text: 'The stress scores and wellness indicators produced by the API must NOT be used for: clinical decision-making,\n    medical diagnoses, medication dosing or treatment decisions, emergency triage, or any safety-critical application.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nefesh-ai/eligibility/nefesh-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Nefesh AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Biometrics
- Human State
- Stress Detection
- Emotion AI
- AI Agents
- MCP
- A2A
- LLM Gateway
- Wearables
- Digital Health
- Middleware
---
