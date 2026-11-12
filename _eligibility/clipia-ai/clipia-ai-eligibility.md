---
api_specs:
- filename: clipia-ai-account-api-openapi.yml
  format: yaml
  label: Clipia.ai Account API
  slug: clipia-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipia-ai/openapi/clipia-ai-account-api-openapi.yml
- filename: clipia-ai-llm-api-openapi.yml
  format: yaml
  label: Clipia.ai LLM API
  slug: clipia-ai-llm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipia-ai/openapi/clipia-ai-llm-api-openapi.yml
- filename: clipia-ai-models-api-openapi.yml
  format: yaml
  label: Clipia.ai Models API
  slug: clipia-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipia-ai/openapi/clipia-ai-models-api-openapi.yml
- filename: clipia-ai-queue-api-openapi.yml
  format: yaml
  label: Clipia.ai Queue API
  slug: clipia-ai-queue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/clipia-ai/openapi/clipia-ai-queue-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'The Service is intended for adults only: you must be at least 18 years old to use the Service.'
    type: individual
  - text: In relationships that are not covered by consumer-protection law (in particular, where the Service is used for commercial purposes by businesses or other legal entities)
    type: business
  minimum_age:
    text: you must be at least 18 years old to use the Service
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: 'The following content is strictly prohibited: Any sexual content involving minors (CSAM)'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to request age verification at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Clipia.ai
provenance_date: '2026-11-09'
provider_name: Clipia.ai
provider_slug: clipia-ai
slug: clipia-ai-eligibility
source_date: '2026-11-09'
source_filename: clipia-ai-eligibility.yml
source_heading: Eligibility
source_page: https://clipia.ai/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clipia.ai\naid: clipia-ai\nurl: https://clipia.ai/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'The Service is intended for adults only: you must be at least 18 years old to use the Service.'\n- type: business\n  text: In relationships that are not covered by consumer-protection law (in particular, where the Service is used\n    for commercial purposes by businesses or other legal entities)\nrestricted_uses:\n- summary: Prohibited content\n  text: 'The following content is strictly prohibited: Any sexual content involving\
  \ minors (CSAM)'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to request age verification at any time.\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old to use the Service\n"
source_yaml_url: https://artifacts.apis.io/clipia-ai/eligibility/clipia-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Clipia.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video Generation
- Image Generation
- Generative AI
- Model Context Protocol
- Text To Video
---
