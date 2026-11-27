---
api_specs:
- filename: segmind-inference-api-openapi.yml
  format: yaml
  label: Segmind Inference API
  slug: segmind-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/segmind/openapi/segmind-inference-api-openapi.yml
- filename: segmind-account-api-openapi.yml
  format: yaml
  label: Segmind Account API
  slug: segmind-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/segmind/openapi/segmind-account-api-openapi.yml
- filename: segmind-storage-api-openapi.yml
  format: yaml
  label: Segmind Storage API
  slug: segmind-storage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/segmind/openapi/segmind-storage-api-openapi.yml
- filename: segmind-fine-tuning-api-openapi.yml
  format: yaml
  label: Segmind Fine-tuning API
  slug: segmind-fine-tuning-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/segmind/openapi/segmind-fine-tuning-api-openapi.yml
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
  - summary: High-risk uses
    text: use the Segmind Services in any circumstances where failure could lead to death, personal injury or environmental damage, and you further acknowledge that the Segmind Services are not designed or intended for such use.
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
name: Segmind
provenance_date: '2026-11-10'
provider_name: Segmind
provider_slug: segmind
slug: segmind-eligibility
source_date: '2026-11-10'
source_filename: segmind-eligibility.yml
source_heading: Eligibility
source_page: https://www.segmind.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Segmind\naid: segmind\nurl: https://www.segmind.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk uses\n  text: use the Segmind Services in any circumstances where failure could lead to death, personal injury or environmental\n    damage, and you further acknowledge that the Segmind Services are not designed or intended for such use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/segmind/eligibility/segmind-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Segmind's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Machine Learning
- Generative AI
- Inference
- Image Generation
- Video Generation
- Serverless
- GPU
- Workflows
- Fine-Tuning
---
