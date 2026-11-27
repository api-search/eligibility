---
api_specs:
- filename: tcgdata-dev-openapi-generated.yml
  format: yaml
  label: tcgdata-dev API
  slug: tcgdata-dev-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tcgdata-dev/openapi/_ae-authored/tcgdata-dev-openapi-generated.yml
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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: After account verification, eligible accounts receive a one-time free test with 500 admitted API calls, valid for 30 days from activation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tcgdata-dev
provenance_date: '2026-11-10'
provider_name: tcgdata-dev
provider_slug: tcgdata-dev
slug: tcgdata-dev-eligibility
source_date: '2026-11-10'
source_filename: tcgdata-dev-eligibility.yml
source_heading: Eligibility
source_page: https://tcgdata.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tcgdata-dev\naid: tcgdata-dev\nurl: https://tcgdata.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: After account verification, eligible accounts receive a one-time free test with 500 admitted API calls,\n    valid for 30 days from activation.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tcgdata-dev/eligibility/tcgdata-dev-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from tcgdata-dev's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Trading Cards
- Pricing
- Europe
---
