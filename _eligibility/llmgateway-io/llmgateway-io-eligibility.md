---
api_specs:
- filename: llmgateway-io-audio-api-openapi.yml
  format: yaml
  label: LLM Gateway Audio API
  slug: llmgateway-io-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-audio-api-openapi.yml
- filename: llmgateway-io-decisions-api-openapi.yml
  format: yaml
  label: LLM Gateway Decisions API
  slug: llmgateway-io-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-decisions-api-openapi.yml
- filename: llmgateway-io-embeddings-api-openapi.yml
  format: yaml
  label: LLM Gateway Embeddings API
  slug: llmgateway-io-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-embeddings-api-openapi.yml
- filename: llmgateway-io-images-api-openapi.yml
  format: yaml
  label: LLM Gateway Images API
  slug: llmgateway-io-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-images-api-openapi.yml
- filename: llmgateway-io-key-api-openapi.yml
  format: yaml
  label: LLM Gateway Key API
  slug: llmgateway-io-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-key-api-openapi.yml
- filename: llmgateway-io-llm-gateway-api-api-openapi.yml
  format: yaml
  label: LLM Gateway LLM Gateway API
  slug: llmgateway-io-llm-gateway-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-llm-gateway-api-api-openapi.yml
- filename: llmgateway-io-messages-api-openapi.yml
  format: yaml
  label: LLM Gateway Messages API
  slug: llmgateway-io-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-messages-api-openapi.yml
- filename: llmgateway-io-models-api-openapi.yml
  format: yaml
  label: LLM Gateway Models API
  slug: llmgateway-io-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-models-api-openapi.yml
- filename: llmgateway-io-moderations-api-openapi.yml
  format: yaml
  label: LLM Gateway Moderations API
  slug: llmgateway-io-moderations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-moderations-api-openapi.yml
- filename: llmgateway-io-ocr-api-openapi.yml
  format: yaml
  label: LLM Gateway Ocr API
  slug: llmgateway-io-ocr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-ocr-api-openapi.yml
- filename: llmgateway-io-realtime-api-openapi.yml
  format: yaml
  label: LLM Gateway Realtime API
  slug: llmgateway-io-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-realtime-api-openapi.yml
- filename: llmgateway-io-rerank-api-openapi.yml
  format: yaml
  label: LLM Gateway Rerank API
  slug: llmgateway-io-rerank-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-rerank-api-openapi.yml
- filename: llmgateway-io-search-api-openapi.yml
  format: yaml
  label: LLM Gateway Search API
  slug: llmgateway-io-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-search-api-openapi.yml
- filename: llmgateway-io-systemone-api-openapi.yml
  format: yaml
  label: LLM Gateway Systemone API
  slug: llmgateway-io-systemone-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-systemone-api-openapi.yml
- filename: llmgateway-io-videos-api-openapi.yml
  format: yaml
  label: LLM Gateway Videos API
  slug: llmgateway-io-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-videos-api-openapi.yml
- filename: llmgateway-io-chat-completions-api-openapi.yml
  format: yaml
  label: LLM Gateway Chat Completions API
  slug: llmgateway-io-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/llmgateway-io/openapi/llmgateway-io-chat-completions-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in, or a resident of, any country or on any list subject to U.S. or other applicable export-control or sanctions restrictions
  entity_types:
  - text: Be at least 18 years old and have the legal capacity to enter into a binding contract;
    type: individual
  - text: If you accept these Terms on behalf of an organization, you represent and warrant that you have the authority to bind that organization
    type: business
  minimum_age:
    text: Be at least 18 years old and have the legal capacity to enter into a binding contract;
    value: '18'
  restricted_uses:
  - summary: High-risk activities
    text: Use the Service in any high-risk activity where failure or inaccuracy could lead to death, personal injury, or severe physical, environmental, or property damage
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may refuse, suspend, or terminate access to anyone at our discretion.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LLM Gateway
provenance_date: '2026-11-09'
provider_name: LLM Gateway
provider_slug: llmgateway-io
slug: llmgateway-io-eligibility
source_date: '2026-11-09'
source_filename: llmgateway-io-eligibility.yml
source_heading: Eligibility
source_page: https://llmgateway.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LLM Gateway\naid: llmgateway-io\nurl: https://llmgateway.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in, or a resident of, any country or on any list subject to U.S.\n    or other applicable export-control or sanctions restrictions\nentity_types:\n- type: individual\n  text: Be at least 18 years old and have the legal capacity to enter into a binding contract;\n- type: business\n  text: If you accept these Terms on behalf of an organization, you represent and warrant that you have the authority\n    to bind that organization\n\
  restricted_uses:\n- summary: High-risk activities\n  text: Use the Service in any high-risk activity where failure or inaccuracy could lead to death, personal injury,\n    or severe physical, environmental, or property damage\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may refuse, suspend, or terminate access to anyone at our discretion.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old and have the legal capacity to enter into a binding contract;\n"
source_yaml_url: https://artifacts.apis.io/llmgateway-io/eligibility/llmgateway-io-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from LLM Gateway's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLM Gateway
- Decision Support
- Structured Outputs
- Inference
- MCP
---
