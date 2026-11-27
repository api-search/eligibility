---
api_specs:
- filename: openrouter-completions-api-openapi.yml
  format: yaml
  label: OpenRouter Completions API
  slug: openrouter-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-completions-api-openapi.yml
- filename: openrouter-credits-api-openapi.yml
  format: yaml
  label: OpenRouter Credits API
  slug: openrouter-credits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-credits-api-openapi.yml
- filename: openrouter-generation-api-openapi.yml
  format: yaml
  label: OpenRouter Generation API
  slug: openrouter-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-generation-api-openapi.yml
- filename: openrouter-keys-api-openapi.yml
  format: yaml
  label: OpenRouter Keys API
  slug: openrouter-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-keys-api-openapi.yml
- filename: openrouter-models-api-openapi.yml
  format: yaml
  label: OpenRouter Models API
  slug: openrouter-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-models-api-openapi.yml
- filename: openrouter-providers-api-openapi.yml
  format: yaml
  label: OpenRouter Providers API
  slug: openrouter-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-providers-api-openapi.yml
- filename: openrouter-chat-completions-api-openapi.yml
  format: yaml
  label: OpenRouter Chat Completions API
  slug: openrouter-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openrouter/openapi/openrouter-chat-completions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use the Service.
    type: individual
  - text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant that you have the authority to bind that organization to these Terms
    type: business
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: Restricted Models access
    text: you may not access these Restricted Models through our Service.
  - summary: Red Teaming
    text: conduct, or work with any third parties to conduct, without OpenRouter's prior written approval, any Red Teaming of Models.
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
name: OpenRouter
provenance_date: '2026-11-10'
provider_name: OpenRouter
provider_slug: openrouter
slug: openrouter-eligibility
source_date: '2026-11-10'
source_filename: openrouter-eligibility.yml
source_heading: Eligibility
source_page: https://openrouter.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenRouter\naid: openrouter\nurl: https://openrouter.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Service.\n- type: business\n  text: If you are using the Service on behalf of an entity, organization, or company, you represent and warrant\n    that you have the authority to bind that organization to these Terms\nrestricted_uses:\n- summary: Restricted Models access\n  text: you may not access these Restricted Models through our Service.\n- summary: Red Teaming\n  text: conduct,\
  \ or work with any third parties to conduct, without OpenRouter's prior written approval, any Red\n    Teaming of Models.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/openrouter/eligibility/openrouter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from OpenRouter's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Gateways
- LLM
- Router
---
