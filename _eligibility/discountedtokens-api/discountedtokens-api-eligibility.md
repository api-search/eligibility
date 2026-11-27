---
api_specs:
- filename: discountedtokens-api-messages-api-openapi.yml
  format: yaml
  label: DiscountedTokens API Messages API
  slug: discountedtokens-api-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discountedtokens-api/openapi/discountedtokens-api-messages-api-openapi.yml
- filename: discountedtokens-api-models-api-openapi.yml
  format: yaml
  label: DiscountedTokens API Models API
  slug: discountedtokens-api-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discountedtokens-api/openapi/discountedtokens-api-models-api-openapi.yml
- filename: discountedtokens-api-responses-api-openapi.yml
  format: yaml
  label: DiscountedTokens API Responses API
  slug: discountedtokens-api-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discountedtokens-api/openapi/discountedtokens-api-responses-api-openapi.yml
- filename: discountedtokens-api-chat-completions-api-openapi.yml
  format: yaml
  label: DiscountedTokens API Chat Completions API
  slug: discountedtokens-api-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/discountedtokens-api/openapi/discountedtokens-api-chat-completions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and legally able to enter a contract.
    type: individual
  minimum_age:
    text: You must be at least 18 and legally able to enter a contract.
    value: '18'
  restricted_uses:
  - summary: High-risk reliance
    text: AI outputs may be incorrect or harmful and require human review.
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
name: DiscountedTokens API
provenance_date: '2026-11-09'
provider_name: DiscountedTokens API
provider_slug: discountedtokens-api
slug: discountedtokens-api-eligibility
source_date: '2026-11-09'
source_filename: discountedtokens-api-eligibility.yml
source_heading: Eligibility
source_page: https://discountedtokens.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DiscountedTokens API\naid: discountedtokens-api\nurl: https://discountedtokens.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and legally able to enter a contract.\nrestricted_uses:\n- summary: High-risk reliance\n  text: AI outputs may be incorrect or harmful and require human review.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and legally able to enter a contract.\n"
source_yaml_url: https://artifacts.apis.io/discountedtokens-api/eligibility/discountedtokens-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from DiscountedTokens API's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- LLM
- Generative AI Inference
- OpenAI-Compatible
- Anthropic Compatible
- API Reseller
- Aggregator
- Prepaid
- Usage-Based
- Developer Tools
- AI Infrastructure
---
