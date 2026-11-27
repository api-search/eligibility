---
api_specs:
- filename: fireflies-transcripts-api-openapi.yml
  format: yaml
  label: Fireflies.ai Transcripts API
  slug: fireflies-transcripts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fireflies/openapi/fireflies-transcripts-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to access or use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to access or use our Services.
    value: '18'
  restricted_uses:
  - summary: No AI as professional advice substitute
    text: Use the AI Services as a companion chatbot or as a substitute for any professional advice (including medical, legal, or financial advice);
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
name: Fireflies.ai
provenance_date: '2026-11-09'
provider_name: Fireflies.ai
provider_slug: fireflies
slug: fireflies-eligibility
source_date: '2026-11-09'
source_filename: fireflies-eligibility.yml
source_heading: Eligibility
source_page: https://fireflies.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fireflies.ai\naid: fireflies\nurl: https://fireflies.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to access or use our Services.\nrestricted_uses:\n- summary: No AI as professional advice substitute\n  text: Use the AI Services as a companion chatbot or as a substitute for any professional advice (including medical,\n    legal, or financial advice);\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: You must be at least 18 years of age to access or use our Services.\n"
source_yaml_url: https://artifacts.apis.io/fireflies/eligibility/fireflies-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fireflies.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Meeting Assistant
- Transcription
- Summary
- Action Items
- GraphQL
- Meetings
- Productivity
- Collaboration
- Conversation Intelligence
- A2A
---
