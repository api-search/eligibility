---
api_specs:
- filename: airouter-ai-router-api-api-openapi.yml
  format: yaml
  label: AI Router AI Router API
  slug: airouter-ai-router-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airouter/openapi/airouter-ai-router-api-api-openapi.yml
- filename: airouter-chat-completions-api-openapi.yml
  format: yaml
  label: AI Router Chat Completions API
  slug: airouter-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/airouter/openapi/airouter-chat-completions-api-openapi.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use certain features of the Service, you may be required to register for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AI Router
provenance_date: '2026-11-09'
provider_name: AI Router
provider_slug: airouter
slug: airouter-eligibility
source_date: '2026-11-09'
source_filename: airouter-eligibility.yml
source_heading: Eligibility
source_page: https://airouter.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AI Router\naid: airouter\nurl: https://airouter.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use certain features of the Service, you may be required to register for an account.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/airouter/eligibility/airouter-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from AI Router's own page on 2026-11-09.
synthetic: false
tags:
- LLM Cost Optimization
- Model Routing
- Enterprise AI
- Privacy
---
