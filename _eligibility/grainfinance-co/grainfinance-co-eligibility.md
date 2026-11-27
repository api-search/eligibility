---
api_specs:
- filename: grainfinance-co-conversions-api-openapi.yml
  format: yaml
  label: Grain Conversions API
  slug: grainfinance-co-conversions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grainfinance-co/openapi/grainfinance-co-conversions-api-openapi.yml
- filename: grainfinance-co-customers-api-openapi.yml
  format: yaml
  label: Grain Customers API
  slug: grainfinance-co-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grainfinance-co/openapi/grainfinance-co-customers-api-openapi.yml
- filename: grainfinance-co-dual-hedges-api-openapi.yml
  format: yaml
  label: Grain Dual Hedges API
  slug: grainfinance-co-dual-hedges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grainfinance-co/openapi/grainfinance-co-dual-hedges-api-openapi.yml
- filename: grainfinance-co-grain-api-api-openapi.yml
  format: yaml
  label: Grain Grain API
  slug: grainfinance-co-grain-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grainfinance-co/openapi/grainfinance-co-grain-api-api-openapi.yml
- filename: grainfinance-co-hedges-api-openapi.yml
  format: yaml
  label: Grain Hedges API
  slug: grainfinance-co-hedges-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grainfinance-co/openapi/grainfinance-co-hedges-api-openapi.yml
- filename: grainfinance-co-payouts-api-openapi.yml
  format: yaml
  label: Grain Payouts API
  slug: grainfinance-co-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grainfinance-co/openapi/grainfinance-co-payouts-api-openapi.yml
- filename: grainfinance-co-pricing-api-openapi.yml
  format: yaml
  label: Grain Pricing API
  slug: grainfinance-co-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grainfinance-co/openapi/grainfinance-co-pricing-api-openapi.yml
- filename: grainfinance-co-vendors-api-openapi.yml
  format: yaml
  label: Grain Vendors API
  slug: grainfinance-co-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grainfinance-co/openapi/grainfinance-co-vendors-api-openapi.yml
- filename: grainfinance-co-wallets-api-openapi.yml
  format: yaml
  label: Grain Wallets API
  slug: grainfinance-co-wallets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/grainfinance-co/openapi/grainfinance-co-wallets-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: YOU DECLARE AND REPRESENT THAT YOU ARE OVER THE AGE OF 18 YEARS OLD
    value: '18'
  restricted_uses:
  - summary: Speculative or investment purpose
    text: (xii) not use the Grain Services for any speculative or investment purpose
  - summary: Illegal or fraudulent use
    text: (viii) use the Grain Services for any illegal or fraudulent purposes
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
name: Grain
provenance_date: '2026-11-09'
provider_name: Grain
provider_slug: grainfinance-co
slug: grainfinance-co-eligibility
source_date: '2026-11-09'
source_filename: grainfinance-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.grainfinance.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grain\naid: grainfinance-co\nurl: https://www.grainfinance.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Speculative or investment purpose\n  text: (xii) not use the Grain Services for any speculative or investment purpose\n- summary: Illegal or fraudulent use\n  text: (viii) use the Grain Services for any illegal or fraudulent purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU DECLARE AND REPRESENT THAT YOU ARE OVER THE AGE\
  \ OF 18 YEARS OLD\n"
source_yaml_url: https://artifacts.apis.io/grainfinance-co/eligibility/grainfinance-co-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Grain's own page on 2026-11-09.
synthetic: false
tags:
- Fintech
- Payments
- Currency
- Embedded
---
