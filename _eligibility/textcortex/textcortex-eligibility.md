---
api_specs:
- filename: textcortex-balance-api-openapi.yml
  format: yaml
  label: Textcortex Balance API
  slug: textcortex-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textcortex/openapi/textcortex-balance-api-openapi.yml
- filename: textcortex-chat-completions-api-openapi.yml
  format: yaml
  label: Textcortex Chat Completions API
  slug: textcortex-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textcortex/openapi/textcortex-chat-completions-api-openapi.yml
- filename: textcortex-models-api-openapi.yml
  format: yaml
  label: Textcortex Models API
  slug: textcortex-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textcortex/openapi/textcortex-models-api-openapi.yml
- filename: textcortex-responses-api-openapi.yml
  format: yaml
  label: Textcortex Responses API
  slug: textcortex-responses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/textcortex/openapi/textcortex-responses-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are available only to individuals who are at least 18 years old
    type: individual
  - text: Organizations may enable an account system with multiple paid seats.
    type: business
  minimum_age:
    text: The Services are available only to individuals who are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Competing service build
    text: To build a similar or competitive service
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
name: Textcortex
provenance_date: '2026-11-10'
provider_name: Textcortex
provider_slug: textcortex
slug: textcortex-eligibility
source_date: '2026-11-10'
source_filename: textcortex-eligibility.yml
source_heading: Eligibility
source_page: https://textcortex.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Textcortex\naid: textcortex\nurl: https://textcortex.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are available only to individuals who are at least 18 years old\n- type: business\n  text: Organizations may enable an account system with multiple paid seats.\nrestricted_uses:\n- summary: Competing service build\n  text: To build a similar or competitive service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are\
  \ available only to individuals who are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/textcortex/eligibility/textcortex-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Textcortex's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Text Generation
- LLM
- Chat Completions
- OpenAI-Compatible
- Content Generation
- Developer Tools
- Foundation Models
---
