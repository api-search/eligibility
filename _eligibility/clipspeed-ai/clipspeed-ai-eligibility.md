---
api_specs:
- filename: clipspeed-ai-openapi-generated.yml
  format: yaml
  label: ClipSpeed API
  slug: clipspeed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipspeed-ai/openapi/_ae-authored/clipspeed-ai-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person — duplicate or fraudulent accounts will be terminated.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful content
    text: Use the Service to generate content that is illegal, harmful, or violates platform policies
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Free accounts receive 30 minutes of processing credit upon verified signup (one-time)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ClipSpeedAI
provenance_date: '2026-11-09'
provider_name: ClipSpeedAI
provider_slug: clipspeed-ai
slug: clipspeed-ai-eligibility
source_date: '2026-11-09'
source_filename: clipspeed-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.clipspeed.ai/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClipSpeedAI\naid: clipspeed-ai\nurl: https://www.clipspeed.ai/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person — duplicate or fraudulent accounts will be terminated.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: Use the Service to generate content that is illegal, harmful, or violates platform policies\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Free accounts receive 30 minutes of processing credit upon verified signup (one-time)\nminimum_age:\n \
  \ value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clipspeed-ai/eligibility/clipspeed-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ClipSpeedAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Video
- Video Clipping
- Image Generation
- Generative AI
- Live Streaming
- Social Media
- MCP
---
