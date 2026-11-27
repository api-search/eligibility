---
api_specs:
- filename: bindry-ai-openapi-generated.yml
  format: yaml
  label: Bindry API
  slug: bindry-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bindry-ai/openapi/_ae-authored/bindry-ai-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We currently send text messages only to phone numbers in the United States and Canada. If your number is elsewhere, you can sign in with your email address instead.
  minimum_age:
    text: You must be at least 16 years old to use the Service.
    value: '16'
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
name: Bindry
provenance_date: '2026-11-09'
provider_name: Bindry
provider_slug: bindry-ai
slug: bindry-ai-eligibility
source_date: '2026-11-09'
source_filename: bindry-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bindry.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bindry\naid: bindry-ai\nurl: https://bindry.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We currently send text messages only to phone numbers in the United States and Canada. If your number is\n    elsewhere, you can sign in with your email address instead.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/bindry-ai/eligibility/bindry-ai-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Bindry's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Package Manager
- Skills
- Developer Tools
- Open Source
- Company
---
