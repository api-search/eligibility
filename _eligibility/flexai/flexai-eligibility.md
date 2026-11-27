---
api_specs:
- filename: flexai-completions-api-openapi.yml
  format: yaml
  label: FlexAI Completions API
  slug: flexai-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-completions-api-openapi.yml
- filename: flexai-embeddings-api-openapi.yml
  format: yaml
  label: FlexAI Embeddings API
  slug: flexai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-embeddings-api-openapi.yml
- filename: flexai-models-api-openapi.yml
  format: yaml
  label: FlexAI Models API
  slug: flexai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-models-api-openapi.yml
- filename: flexai-usage-api-openapi.yml
  format: yaml
  label: FlexAI Usage API
  slug: flexai-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-usage-api-openapi.yml
- filename: flexai-chat-completions-api-openapi.yml
  format: yaml
  label: FlexAI Chat Completions API
  slug: flexai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/flexai/openapi/flexai-chat-completions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: otherwise, such terms refer to you as a natural person.
    type: individual
  - text: if you are operating on behalf of another entity, you are authorized to bind that entity to this agreement
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Outputs not for legal, medical or regulated decisions
    text: Customers should not rely on outputs for legal, medical, employment, safety-critical, or regulated decisions.
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
name: FlexAI
provenance_date: '2026-11-09'
provider_name: FlexAI
provider_slug: flexai
slug: flexai-eligibility
source_date: '2026-11-09'
source_filename: flexai-eligibility.yml
source_heading: Eligibility
source_page: https://flex.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FlexAI\naid: flexai\nurl: https://flex.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: otherwise, such terms refer to you as a natural person.\n- type: business\n  text: if you are operating on behalf of another entity, you are authorized to bind that entity to this agreement\nrestricted_uses:\n- summary: Outputs not for legal, medical or regulated decisions\n  text: Customers should not rely on outputs for legal, medical, employment, safety-critical, or regulated decisions.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/flexai/eligibility/flexai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from FlexAI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Inference
- LLM
- OpenAI-Compatible
- GPU Compute
- Embeddings
- Fine-Tuning
- Agents
---
