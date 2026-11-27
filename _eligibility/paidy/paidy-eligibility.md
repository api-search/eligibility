---
api_specs:
- filename: paidy-payments-api-openapi.yml
  format: yaml
  label: Paidy Payments API
  slug: paidy-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidy/openapi/paidy-payments-api-openapi.yml
- filename: paidy-tokens-api-openapi.yml
  format: yaml
  label: Paidy Tokens API
  slug: paidy-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paidy/openapi/paidy-tokens-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 法人のお客様
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 加盟店審査 追加情報が必要な場合がございます。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Paidy
provenance_date: '2026-11-10'
provider_name: Paidy
provider_slug: paidy
slug: paidy-eligibility
source_date: '2026-11-10'
source_filename: paidy-eligibility.yml
source_heading: Eligibility
source_page: https://paidy.com/merchant/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paidy\naid: paidy\nurl: https://paidy.com/merchant/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: 法人のお客様\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 加盟店審査 追加情報が必要な場合がございます。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/paidy/eligibility/paidy-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Paidy's own page on 2026-11-10.
synthetic: false
tags:
- Buy Now Pay Later
- Payments
- Japan
- Checkout
- Deferred Payments
- Recurring Payments
- Tokens
---
