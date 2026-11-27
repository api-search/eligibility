---
api_specs:
- filename: exactly-ai-images-v1-api-openapi.yml
  format: yaml
  label: Exactly Ai Images v1 API
  slug: exactly-ai-images-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exactly-ai/openapi/exactly-ai-images-v1-api-openapi.yml
- filename: exactly-ai-models-v1-api-openapi.yml
  format: yaml
  label: Exactly Ai Models v1 API
  slug: exactly-ai-models-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/exactly-ai/openapi/exactly-ai-models-v1-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: User has reached the age of majority in the jurisdiction where User resides
    value: null
  restricted_uses:
  - summary: Watermarked generations evaluation only
    text: Watermarked Generations are provided solely for the User's internal review and evaluation of the content and quality
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Company reserves the right to carry out the User Verification Process in relation to User's access to certain features and functionality on the Platform
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Exactly Ai
provenance_date: '2026-11-09'
provider_name: Exactly Ai
provider_slug: exactly-ai
slug: exactly-ai-eligibility
source_date: '2026-11-09'
source_filename: exactly-ai-eligibility.yml
source_heading: Eligibility
source_page: https://exactly.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Exactly Ai\naid: exactly-ai\nurl: https://exactly.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Watermarked generations evaluation only\n  text: Watermarked Generations are provided solely for the User's internal review and evaluation of the content\n    and quality\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Company reserves the right to carry out the User Verification Process in relation to User's access to certain\n    features and functionality on the Platform\n\
  minimum_age:\n  value: null\n  text: User has reached the age of majority in the jurisdiction where User resides\n"
source_yaml_url: https://artifacts.apis.io/exactly-ai/eligibility/exactly-ai-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Exactly Ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Image Generation
- Generative AI
- Creative Tools
- Brands
- Machine Learning
- Media
---
