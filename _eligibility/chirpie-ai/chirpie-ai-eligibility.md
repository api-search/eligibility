---
api_specs:
- filename: chirpie-ai-openapi-generated.yml
  format: yaml
  label: Chirpie API
  slug: chirpie-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chirpie-ai/openapi/_ae-authored/chirpie-ai-openapi-generated.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use the Service.
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
name: Chirpie
provenance_date: '2026-11-09'
provider_name: Chirpie
provider_slug: chirpie-ai
slug: chirpie-ai-eligibility
source_date: '2026-11-09'
source_filename: chirpie-ai-eligibility.yml
source_heading: Eligibility
source_page: https://chirpie.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chirpie\naid: chirpie-ai\nurl: https://chirpie.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/chirpie-ai/eligibility/chirpie-ai-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Chirpie's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Media
- Social Media Posting
- Scheduling
- MCP
- AI Agents
- Analytics
---
