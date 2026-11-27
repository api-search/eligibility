---
api_specs:
- filename: standard-compute-completions-api-openapi.yml
  format: yaml
  label: Standard Compute Completions API
  slug: standard-compute-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-completions-api-openapi.yml
- filename: standard-compute-healthz-api-openapi.yml
  format: yaml
  label: Standard Compute Healthz API
  slug: standard-compute-healthz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-healthz-api-openapi.yml
- filename: standard-compute-install-ps1-api-openapi.yml
  format: yaml
  label: Standard Compute Install.ps1 API
  slug: standard-compute-install-ps1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-install-ps1-api-openapi.yml
- filename: standard-compute-install-sh-api-openapi.yml
  format: yaml
  label: Standard Compute Install.sh API
  slug: standard-compute-install-sh-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-install-sh-api-openapi.yml
- filename: standard-compute-messages-api-openapi.yml
  format: yaml
  label: Standard Compute Messages API
  slug: standard-compute-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-messages-api-openapi.yml
- filename: standard-compute-models-api-openapi.yml
  format: yaml
  label: Standard Compute Models API
  slug: standard-compute-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-models-api-openapi.yml
- filename: standard-compute-responses-api-openapi.yml
  format: yaml
  label: Standard Compute Responses API
  slug: standard-compute-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-responses-api-openapi.yml
- filename: standard-compute-chat-completions-api-openapi.yml
  format: yaml
  label: Standard Compute Chat Completions API
  slug: standard-compute-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/standard-compute/openapi/standard-compute-chat-completions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Individual plans are currently Starter, Economy, Standard, and Pro.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or harmful content
    text: You may not use the service to generate content that is illegal, harmful, or violates the acceptable-use policies of the upstream model providers.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide a valid email address to create an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Standard Compute
provenance_date: '2026-11-10'
provider_name: Standard Compute
provider_slug: standard-compute
slug: standard-compute-eligibility
source_date: '2026-11-10'
source_filename: standard-compute-eligibility.yml
source_heading: Eligibility
source_page: https://standardcompute.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Standard Compute\naid: standard-compute\nurl: https://standardcompute.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Individual plans are currently Starter, Economy, Standard, and Pro.\nrestricted_uses:\n- summary: Illegal or harmful content\n  text: You may not use the service to generate content that is illegal, harmful, or violates the acceptable-use\n    policies of the upstream model providers.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide a valid email address to create\
  \ an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/standard-compute/eligibility/standard-compute-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Standard Compute's own page on 2026-11-10.
synthetic: false
tags:
- LLM API
- Flat-rate
- Subscription
- AI Agents
- Inference
- Model Routing
- AI Gateway
- Developer Tools
- Coding Agents
- OpenAI-Compatible
---
