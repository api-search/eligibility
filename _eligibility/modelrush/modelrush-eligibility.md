---
api_specs:
- filename: modelrush-audio-api-openapi.yml
  format: yaml
  label: ModelRush Audio API
  slug: modelrush-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-audio-api-openapi.yml
- filename: modelrush-discovery-api-openapi.yml
  format: yaml
  label: ModelRush Discovery API
  slug: modelrush-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-discovery-api-openapi.yml
- filename: modelrush-images-api-openapi.yml
  format: yaml
  label: ModelRush Images API
  slug: modelrush-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-images-api-openapi.yml
- filename: modelrush-predictions-api-openapi.yml
  format: yaml
  label: ModelRush Predictions API
  slug: modelrush-predictions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-predictions-api-openapi.yml
- filename: modelrush-uploads-api-openapi.yml
  format: yaml
  label: ModelRush Uploads API
  slug: modelrush-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-uploads-api-openapi.yml
- filename: modelrush-video-api-openapi.yml
  format: yaml
  label: ModelRush Video API
  slug: modelrush-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-video-api-openapi.yml
- filename: modelrush-webhooks-api-openapi.yml
  format: yaml
  label: ModelRush Webhooks API
  slug: modelrush-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-webhooks-api-openapi.yml
- filename: modelrush-chat-completions-api-openapi.yml
  format: yaml
  label: ModelRush Chat Completions API
  slug: modelrush-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/modelrush/openapi/modelrush-chat-completions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the service for an organization, you represent that you can bind that organization.
    type: business
  minimum_age:
    text: Restricted models are available only to users who have truthfully confirmed they are at least 18
    value: '18'
  restricted_uses:
  - summary: Restricted models limited to users aged 18+
    text: Restricted models are available only to users who have truthfully confirmed they are at least 18
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
name: ModelRush
provenance_date: '2026-11-10'
provider_name: ModelRush
provider_slug: modelrush
slug: modelrush-eligibility
source_date: '2026-11-10'
source_filename: modelrush-eligibility.yml
source_heading: Eligibility
source_page: https://modelrush.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ModelRush\naid: modelrush\nurl: https://modelrush.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the service for an organization, you represent that you can bind that organization.\nrestricted_uses:\n- summary: Restricted models limited to users aged 18+\n  text: Restricted models are available only to users who have truthfully confirmed they are at least 18\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Restricted models are available only\
  \ to users who have truthfully confirmed they are at least 18\n"
source_yaml_url: https://artifacts.apis.io/modelrush/eligibility/modelrush-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ModelRush's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Inference
- Multi-Modal
- Model Hosting
- Speech
- Image Generation
---
