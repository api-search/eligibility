---
api_specs:
- filename: venice-ai-api-keys-api-openapi.yml
  format: yaml
  label: Venice.ai API Keys API
  slug: venice-ai-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-api-keys-api-openapi.yml
- filename: venice-ai-audio-api-openapi.yml
  format: yaml
  label: Venice.ai Audio API
  slug: venice-ai-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-audio-api-openapi.yml
- filename: venice-ai-augment-api-openapi.yml
  format: yaml
  label: Venice.ai Augment API
  slug: venice-ai-augment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-augment-api-openapi.yml
- filename: venice-ai-billing-api-openapi.yml
  format: yaml
  label: Venice.ai Billing API
  slug: venice-ai-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-billing-api-openapi.yml
- filename: venice-ai-characters-api-openapi.yml
  format: yaml
  label: Venice.ai Characters API
  slug: venice-ai-characters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-characters-api-openapi.yml
- filename: venice-ai-crypto-rpc-api-openapi.yml
  format: yaml
  label: Venice.ai Crypto RPC API
  slug: venice-ai-crypto-rpc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-crypto-rpc-api-openapi.yml
- filename: venice-ai-decisions-api-openapi.yml
  format: yaml
  label: Venice.ai Decisions API
  slug: venice-ai-decisions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-decisions-api-openapi.yml
- filename: venice-ai-embeddings-api-openapi.yml
  format: yaml
  label: Venice.ai Embeddings API
  slug: venice-ai-embeddings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-embeddings-api-openapi.yml
- filename: venice-ai-image-api-openapi.yml
  format: yaml
  label: Venice.ai Image API
  slug: venice-ai-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-image-api-openapi.yml
- filename: venice-ai-models-api-openapi.yml
  format: yaml
  label: Venice.ai Models API
  slug: venice-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-models-api-openapi.yml
- filename: venice-ai-preview-api-openapi.yml
  format: yaml
  label: Venice.ai Preview API
  slug: venice-ai-preview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-preview-api-openapi.yml
- filename: venice-ai-responses-api-openapi.yml
  format: yaml
  label: Venice.ai Responses API
  slug: venice-ai-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-responses-api-openapi.yml
- filename: venice-ai-speech-api-openapi.yml
  format: yaml
  label: Venice.ai Speech API
  slug: venice-ai-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-speech-api-openapi.yml
- filename: venice-ai-transcriptions-api-openapi.yml
  format: yaml
  label: Venice.ai Transcriptions API
  slug: venice-ai-transcriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-transcriptions-api-openapi.yml
- filename: venice-ai-video-api-openapi.yml
  format: yaml
  label: Venice.ai Video API
  slug: venice-ai-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-video-api-openapi.yml
- filename: venice-ai-voices-api-openapi.yml
  format: yaml
  label: Venice.ai Voices API
  slug: venice-ai-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-voices-api-openapi.yml
- filename: venice-ai-x402-api-openapi.yml
  format: yaml
  label: Venice.ai X402 API
  slug: venice-ai-x402-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-x402-api-openapi.yml
- filename: venice-ai-chat-completions-api-openapi.yml
  format: yaml
  label: Venice.ai Chat Completions API
  slug: venice-ai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/venice-ai/openapi/venice-ai-chat-completions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is intended for visitors located within the United States. We make no representation that the Service is appropriate or available for use outside of the United States.
  entity_types:
  - text: You must be at least 13 years old to use the Service.
    type: individual
  - text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents and warrants that they have authority to bind you to these Terms
    type: business
  minimum_age:
    text: You must be at least 13 years old to use the Service. If you are under eighteen (18) years of age, then you must have a parent or guardian’s consent to use the Service.
    value: '13'
  restricted_uses:
  - summary: High-stakes API use
    text: use the API in connection with use case where the failure or inaccuracy of AI-generated outputs could reasonably be expected to result in death, serious bodily injury, or significant physical, financial, or safety harm to individuals.
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
name: Venice.ai
provenance_date: '2026-11-10'
provider_name: Venice.ai
provider_slug: venice-ai
slug: venice-ai-eligibility
source_date: '2026-11-10'
source_filename: venice-ai-eligibility.yml
source_heading: Eligibility
source_page: https://venice.ai/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Venice.ai\naid: venice-ai\nurl: https://venice.ai/legal/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Service is intended for visitors located within the United States. We make no representation that the\n    Service is appropriate or available for use outside of the United States.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service.\n- type: business\n  text: If you are an entity, organization, or company, the individual accepting these Terms on your behalf represents\n    and warrants that they have authority\
  \ to bind you to these Terms\nrestricted_uses:\n- summary: High-stakes API use\n  text: use the API in connection with use case where the failure or inaccuracy of AI-generated outputs could reasonably\n    be expected to result in death, serious bodily injury, or significant physical, financial, or safety harm to\n    individuals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service. If you are under eighteen (18) years of age, then\n    you must have a parent or guardian’s consent to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/venice-ai/eligibility/venice-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Venice.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- Image Generation
- Video Generation
- Text-to-Speech
- Embeddings
- Privacy
- OpenAI-Compatible
- x402
---
