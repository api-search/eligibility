---
api_specs:
- filename: edgee-compress-api-openapi.yml
  format: yaml
  label: Edgee Compress API
  slug: edgee-compress-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-compress-api-openapi.yml
- filename: edgee-messages-api-openapi.yml
  format: yaml
  label: Edgee Messages API
  slug: edgee-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-messages-api-openapi.yml
- filename: edgee-models-api-openapi.yml
  format: yaml
  label: Edgee Models API
  slug: edgee-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-models-api-openapi.yml
- filename: edgee-responses-api-openapi.yml
  format: yaml
  label: Edgee Responses API
  slug: edgee-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-responses-api-openapi.yml
- filename: edgee-tokens-api-openapi.yml
  format: yaml
  label: Edgee Tokens API
  slug: edgee-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-tokens-api-openapi.yml
- filename: edgee-chat-completions-api-openapi.yml
  format: yaml
  label: Edgee Chat Completions API
  slug: edgee-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edgee/openapi/edgee-chat-completions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You have the authority to bind the legal entity (the "Customer") you represent.
    type: business
  minimum_age:
    text: You are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive content
    text: Use the Services to transmit unlawful, abusive, or harmful content.
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
name: Edgee
provenance_date: '2026-11-09'
provider_name: Edgee
provider_slug: edgee
slug: edgee-eligibility
source_date: '2026-11-09'
source_filename: edgee-eligibility.yml
source_heading: Eligibility
source_page: https://www.edgee.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Edgee\naid: edgee\nurl: https://www.edgee.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: You have the authority to bind the legal entity (the \"Customer\") you represent.\nrestricted_uses:\n- summary: Unlawful or abusive content\n  text: Use the Services to transmit unlawful, abusive, or harmful content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/edgee/eligibility/edgee-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Edgee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- LLM
- AI Gateway
- Agents
- Developer Tools
- Observability
- FinOps
- Edge Computing
- Cost Management
---
