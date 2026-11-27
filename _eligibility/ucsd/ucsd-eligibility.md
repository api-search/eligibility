---
api_specs:
- filename: ucsd-completions-api-openapi.yml
  format: yaml
  label: TritonAI Developer API — completions
  slug: tritonai-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ucsd/openapi/ucsd-completions-api-openapi.yml
- filename: ucsd-embeddings-api-openapi.yml
  format: yaml
  label: TritonAI Developer API — embeddings
  slug: tritonai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ucsd/openapi/ucsd-embeddings-api-openapi.yml
- filename: ucsd-models-api-openapi.yml
  format: yaml
  label: TritonAI Developer API — models
  slug: tritonai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ucsd/openapi/ucsd-models-api-openapi.yml
- filename: ucsd-images-api-openapi.yml
  format: yaml
  label: TritonAI Developer API — images
  slug: tritonai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ucsd/openapi/ucsd-images-api-openapi.yml
- filename: ucsd-audio-api-openapi.yml
  format: yaml
  label: TritonAI Developer API — audio
  slug: tritonai-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ucsd/openapi/ucsd-audio-api-openapi.yml
- filename: ucsd-scim-api-openapi.yml
  format: yaml
  label: TritonAI Developer API — SCIM 2.0 provisioning
  slug: tritonai-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ucsd/openapi/ucsd-scim-api-openapi.yml
- filename: ucsd-objects-api-openapi.yml
  format: yaml
  label: University of California, San Diego Objects API
  slug: ucsd-objects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ucsd/openapi/ucsd-objects-api-openapi.yml
- filename: ucsd-search-api-openapi.yml
  format: yaml
  label: University of California, San Diego Search API
  slug: ucsd-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ucsd/openapi/ucsd-search-api-openapi.yml
- filename: ucsd-chat-completions-api-openapi.yml
  format: yaml
  label: University of California, San Diego Chat Completions API
  slug: ucsd-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ucsd/openapi/ucsd-chat-completions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Employees and students of UC San Diego campus and health sciences are authorized to use TritonGPT.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for personal or commercial use
    text: It is not intended for personal or commercial use, or to generate output that students would submit for credit.
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
name: University of California, San Diego
provenance_date: '2026-11-10'
provider_name: University of California, San Diego
provider_slug: ucsd
slug: ucsd-eligibility
source_date: '2026-11-10'
source_filename: ucsd-eligibility.yml
source_heading: Eligibility
source_page: https://tritonai.ucsd.edu/tritongpt/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: University of California, San Diego\naid: ucsd\nurl: https://tritonai.ucsd.edu/tritongpt/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Employees and students of UC San Diego campus and health sciences are authorized to use TritonGPT.\nrestricted_uses:\n- summary: Not for personal or commercial use\n  text: It is not intended for personal or commercial use, or to generate output that students would submit for\n    credit.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n \
  \ value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ucsd/eligibility/ucsd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from University of California, San Diego's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Higher Education
- University
- Public Research University
- UC System
- United States
- California
- Research
- Research Data
- Digital Collections
- Identity Federation
- API Gateway
- Artificial Intelligence
- Research Computing
---
