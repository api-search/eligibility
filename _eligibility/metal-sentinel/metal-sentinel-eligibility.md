---
api_specs:
- filename: metal-sentinel-api-openapi.json
  format: json
  label: Metal Sentinel API API
  slug: metal-sentinel-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metal-sentinel/openapi/_original/metal-sentinel-api-openapi.json
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
  restricted_uses:
  - summary: Unlawful use
    text: You may not use the Service for any unlawful purpose or in violation of any applicable laws.
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
name: Metal Sentinel
provenance_date: '2026-11-10'
provider_name: Metal Sentinel
provider_slug: metal-sentinel
slug: metal-sentinel-eligibility
source_date: '2026-11-10'
source_filename: metal-sentinel-eligibility.yml
source_heading: Eligibility
source_page: https://metal-sentinel.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Metal Sentinel\naid: metal-sentinel\nurl: https://metal-sentinel.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: You may not use the Service for any unlawful purpose or in violation of any applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/metal-sentinel/eligibility/metal-sentinel-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Metal Sentinel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Data
- Metals
- Real-Time
---
