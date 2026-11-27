---
api_specs:
- filename: rightnow-audio-api-openapi.yml
  format: yaml
  label: RightNow AI Audio API
  slug: rightnow-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-audio-api-openapi.yml
- filename: rightnow-embeddings-api-openapi.yml
  format: yaml
  label: RightNow AI Embeddings API
  slug: rightnow-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-embeddings-api-openapi.yml
- filename: rightnow-images-api-openapi.yml
  format: yaml
  label: RightNow AI Images API
  slug: rightnow-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-images-api-openapi.yml
- filename: rightnow-models-api-openapi.yml
  format: yaml
  label: RightNow AI Models API
  slug: rightnow-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-models-api-openapi.yml
- filename: rightnow-rerank-api-openapi.yml
  format: yaml
  label: RightNow AI Rerank API
  slug: rightnow-rerank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-rerank-api-openapi.yml
- filename: rightnow-responses-api-openapi.yml
  format: yaml
  label: RightNow AI Responses API
  slug: rightnow-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-responses-api-openapi.yml
- filename: rightnow-chat-completions-api-openapi.yml
  format: yaml
  label: RightNow AI Chat Completions API
  slug: rightnow-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rightnow/openapi/rightnow-chat-completions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided when using the Services is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.
  entity_types:
  - text: whether personally or on behalf of an entity ("you"), and RightNow AI, Inc.
    type: business
  minimum_age:
    text: All users who are minors in their jurisdiction (generally under 18) must have the permission of, and be directly supervised by, their parent or guardian to use the Services.
    value: '18'
  restricted_uses:
  - summary: Deploying models that produce illegal content
    text: Use the Services to deploy models that produce illegal content
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
name: RightNow AI
provenance_date: '2026-11-10'
provider_name: RightNow AI
provider_slug: rightnow
slug: rightnow-eligibility
source_date: '2026-11-10'
source_filename: rightnow-eligibility.yml
source_heading: Eligibility
source_page: https://runinfra.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RightNow AI\naid: rightnow\nurl: https://runinfra.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided when using the Services is not intended for distribution to or use by any person\n    or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation.\nentity_types:\n- type: business\n  text: whether personally or on behalf of an entity (\"you\"), and RightNow AI, Inc.\nrestricted_uses:\n- summary: Deploying models that produce illegal content\n  text: Use the Services to deploy models that produce\
  \ illegal content\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All users who are minors in their jurisdiction (generally under 18) must have the permission of, and be\n    directly supervised by, their parent or guardian to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/rightnow/eligibility/rightnow-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from RightNow AI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Inference
- GPU
- Model Deployment
- Serverless
- OpenAI-Compatible
- Embeddings
- MLOps
---
