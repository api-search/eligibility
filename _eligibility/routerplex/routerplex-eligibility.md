---
api_specs:
- filename: routerplex-images-api-openapi.yml
  format: yaml
  label: RouterPlex Images API
  slug: routerplex-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-images-api-openapi.yml
- filename: routerplex-messages-api-openapi.yml
  format: yaml
  label: RouterPlex Messages API
  slug: routerplex-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-messages-api-openapi.yml
- filename: routerplex-models-api-openapi.yml
  format: yaml
  label: RouterPlex Models API
  slug: routerplex-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-models-api-openapi.yml
- filename: routerplex-responses-api-openapi.yml
  format: yaml
  label: RouterPlex Responses API
  slug: routerplex-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-responses-api-openapi.yml
- filename: routerplex-chat-completions-api-openapi.yml
  format: yaml
  label: RouterPlex Chat Completions API
  slug: routerplex-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/routerplex/openapi/routerplex-chat-completions-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Service if you are located in, or are a national or resident of, a country or region subject to comprehensive sanctions, or if you are named on a government sanctions or restricted-party list.
  entity_types:
  - text: You must be at least 18 years old, or the age of majority where you live if higher, to use the Service.
    type: individual
  - text: One person or legal entity may hold only one account; creating multiple accounts to collect promotional credit repeatedly is prohibited.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live if higher, to use the Service.
    value: '18'
  restricted_uses:
  - summary: Sanctioned locations or parties
    text: You may not use the Service if you are located in, or are a national or resident of, a country or region subject to comprehensive sanctions
  - summary: Sexual content involving minors
    text: generate, request, or facilitate any content that sexualises, exploits, or abuses minors
  - summary: Abliterated model restrictions
    text: 'you must not use abliterated models to: design, develop, build, acquire, or use weapons'
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
name: RouterPlex
provenance_date: '2026-11-10'
provider_name: RouterPlex
provider_slug: routerplex
slug: routerplex-eligibility
source_date: '2026-11-10'
source_filename: routerplex-eligibility.yml
source_heading: Eligibility
source_page: https://routerplex.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RouterPlex\naid: routerplex\nurl: https://routerplex.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Service if you are located in, or are a national or resident of, a country or region\n    subject to comprehensive sanctions, or if you are named on a government sanctions or restricted-party list.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live if higher, to use the Service.\n- type: business\n  text: One person or legal entity may hold only one account; creating multiple accounts to\
  \ collect promotional\n    credit repeatedly is prohibited.\nrestricted_uses:\n- summary: Sanctioned locations or parties\n  text: You may not use the Service if you are located in, or are a national or resident of, a country or region\n    subject to comprehensive sanctions\n- summary: Sexual content involving minors\n  text: generate, request, or facilitate any content that sexualises, exploits, or abuses minors\n- summary: Abliterated model restrictions\n  text: 'you must not use abliterated models to: design, develop, build, acquire, or use weapons'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live if higher, to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/routerplex/eligibility/routerplex-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from RouterPlex's own page on 2026-11-10.
synthetic: false
tags:
- LLM
- Artificial Intelligence
- AI Gateway
- Inference
- Model Router
- OpenAI-Compatible
- Anthropic Compatible
- Claude
- GPT
- Gemini
- API Gateway
- Agent Infrastructure
- Developer Tools
- MCP
- LLMOps
---
