---
api_specs:
- filename: bibigpt-co-api-openapi.json
  format: json
  label: BibiGPT OpenAPI 规范 API
  slug: bibigpt-openapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bibigpt-co/openapi/_original/bibigpt-co-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are available to individuals who are at least 13 years old.
    type: individual
  minimum_age:
    text: The Services are available to individuals who are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Commercial bulk use of unlimited tiers
    text: use the account to provide commercial services to others in bulk
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
name: BibiGPT
provenance_date: '2026-11-09'
provider_name: BibiGPT
provider_slug: bibigpt-co
slug: bibigpt-co-eligibility
source_date: '2026-11-09'
source_filename: bibigpt-co-eligibility.yml
source_heading: Eligibility
source_page: https://bibigpt.co/en/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BibiGPT\naid: bibigpt-co\nurl: https://bibigpt.co/en/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are available to individuals who are at least 13 years old.\nrestricted_uses:\n- summary: Commercial bulk use of unlimited tiers\n  text: use the account to provide commercial services to others in bulk\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are available to individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/bibigpt-co/eligibility/bibigpt-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BibiGPT's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video Summarization
- Multilingual
- Free
- Web App
---
