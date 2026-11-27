---
api_specs:
- filename: app-avots-ai-openapi.json
  format: json
  label: OpenAI-compatible API
  slug: openai-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/avots-ai/openapi/app-avots-ai-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to create an account
    value: '16'
  restricted_uses:
  - summary: Illegal or harmful use
    text: Use the Service to harm, harass, or deceive others
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
name: avots.ai
provenance_date: '2026-11-09'
provider_name: avots.ai
provider_slug: avots-ai
slug: avots-ai-eligibility
source_date: '2026-11-09'
source_filename: avots-ai-eligibility.yml
source_heading: Eligibility
source_page: https://avots.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: avots.ai\naid: avots-ai\nurl: https://avots.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: Use the Service to harm, harass, or deceive others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to create an account\n"
source_yaml_url: https://artifacts.apis.io/avots-ai/eligibility/avots-ai-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from avots.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Subscription
- Generative AI
- Platform
- Aggregator
---
