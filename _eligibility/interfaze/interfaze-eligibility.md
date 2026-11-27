---
api_specs:
- filename: interfaze-chat-completions-api-openapi.yml
  format: yaml
  label: Interfaze Chat Completions API
  slug: interfaze-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/interfaze/openapi/interfaze-chat-completions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: are at least 18 years old, or 13 years or older and have the express permission of your parent or guardian to use the Services
    type: individual
  - text: if using the Services on behalf of an organization, have the authority to bind that organization to these Terms.
    type: business
  minimum_age:
    text: are at least 18 years old, or 13 years or older and have the express permission of your parent or guardian to use the Services
    value: '13'
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
name: Interfaze
provenance_date: '2026-11-09'
provider_name: Interfaze
provider_slug: interfaze
slug: interfaze-eligibility
source_date: '2026-11-09'
source_filename: interfaze-eligibility.yml
source_heading: Eligibility
source_page: https://interfaze.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Interfaze\naid: interfaze\nurl: https://interfaze.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: are at least 18 years old, or 13 years or older and have the express permission of your parent or guardian\n    to use the Services\n- type: business\n  text: if using the Services on behalf of an organization, have the authority to bind that organization to these\n    Terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: are at\
  \ least 18 years old, or 13 years or older and have the express permission of your parent or guardian\n    to use the Services\n"
source_yaml_url: https://artifacts.apis.io/interfaze/eligibility/interfaze-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Interfaze's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- LLM
- OCR
- Speech-to-Text
- Structured Output
- Object Detection
- Web Scraping
- Web Search
- Multi-Modal
- Developer Tools
- A2A
---
