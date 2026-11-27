---
api_specs:
- filename: bumit-ai-v1-openapi.json
  format: json
  label: BUMIT API V1 API
  slug: bumit-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bumit-ai/openapi/_original/bumit-ai-v1-openapi.json
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - CH
    text: Coverage is limited to Switzerland and to the capabilities listed as available.
  minimum_age:
    text: null
    value: null
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
name: BUMIT
provenance_date: '2026-11-09'
provider_name: BUMIT
provider_slug: bumit-ai
slug: bumit-ai-eligibility
source_date: '2026-11-09'
source_filename: bumit-ai-eligibility.yml
source_heading: Eligibility
source_page: https://bumit.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BUMIT\naid: bumit-ai\nurl: https://bumit.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CH\n  excluded: []\n  text: Coverage is limited to Switzerland and to the capabilities listed as available.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bumit-ai/eligibility/bumit-ai-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from BUMIT's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trust
- Verification
- Swiss
---
