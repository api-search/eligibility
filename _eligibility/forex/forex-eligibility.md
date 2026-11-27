---
api_specs:
- filename: forex-account-api-openapi.yml
  format: yaml
  label: Forex Account API
  slug: forex-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forex/openapi/forex-account-api-openapi.yml
- filename: forex-rates-api-openapi.yml
  format: yaml
  label: Forex Rates API
  slug: forex-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forex/openapi/forex-rates-api-openapi.yml
- filename: forex-reference-api-openapi.yml
  format: yaml
  label: Forex Reference API
  slug: forex-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/forex/openapi/forex-reference-api-openapi.yml
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
  - summary: Data only for end purposes
    text: ExchangeRate-API data may only be used for your end purposes and not in any product or service that offers programmatic or automatic access to exchange rate data.
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
name: Forex
provenance_date: '2026-11-09'
provider_name: Forex
provider_slug: forex
slug: forex-eligibility
source_date: '2026-11-09'
source_filename: forex-eligibility.yml
source_heading: Eligibility
source_page: https://www.exchangerate-api.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Forex\naid: forex\nurl: https://www.exchangerate-api.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Data only for end purposes\n  text: ExchangeRate-API data may only be used for your end purposes and not in any product or service that offers\n    programmatic or automatic access to exchange rate data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/forex/eligibility/forex-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Forex's own page on 2026-11-09.
synthetic: false
tags:
- Currency
- Exchange Rates
- Financial Data
- Foreign Exchange
- Trading
---
