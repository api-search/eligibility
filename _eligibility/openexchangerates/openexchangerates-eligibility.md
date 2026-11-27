---
api_specs:
- filename: openexchangerates-convert-api-openapi.yml
  format: yaml
  label: Open Exchange Rates Convert API
  slug: openexchangerates-convert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openexchangerates/openapi/openexchangerates-convert-api-openapi.yml
- filename: openexchangerates-currencies-api-openapi.yml
  format: yaml
  label: Open Exchange Rates Currencies API
  slug: openexchangerates-currencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openexchangerates/openapi/openexchangerates-currencies-api-openapi.yml
- filename: openexchangerates-ohlc-api-openapi.yml
  format: yaml
  label: Open Exchange Rates OHLC API
  slug: openexchangerates-ohlc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openexchangerates/openapi/openexchangerates-ohlc-api-openapi.yml
- filename: openexchangerates-time-series-api-openapi.yml
  format: yaml
  label: Open Exchange Rates Time Series API
  slug: openexchangerates-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openexchangerates/openapi/openexchangerates-time-series-api-openapi.yml
- filename: openexchangerates-usage-api-openapi.yml
  format: yaml
  label: Open Exchange Rates Usage API
  slug: openexchangerates-usage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openexchangerates/openapi/openexchangerates-usage-api-openapi.yml
- filename: openexchangerates-rates-api-openapi.yml
  format: yaml
  label: Open Exchange Rates API
  slug: openexchangerates-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openexchangerates/openapi/openexchangerates-rates-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a private consumer user, please note that we only provide our site for domestic and private use.
    type: individual
  - text: 'If you are a business user, please note that in particular, we will not be liable for:'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Domestic and private use only
    text: we only provide our site for domestic and private use. You agree not to use our site for any commercial or business purposes
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
name: Open Exchange Rates
provenance_date: '2026-11-10'
provider_name: Open Exchange Rates
provider_slug: openexchangerates
slug: openexchangerates-eligibility
source_date: '2026-11-10'
source_filename: openexchangerates-eligibility.yml
source_heading: Eligibility
source_page: https://openexchangerates.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Open Exchange Rates\naid: openexchangerates\nurl: https://openexchangerates.org/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a private consumer user, please note that we only provide our site for domestic and private use.\n- type: business\n  text: 'If you are a business user, please note that in particular, we will not be liable for:'\nrestricted_uses:\n- summary: Domestic and private use only\n  text: we only provide our site for domestic and private use. You agree not to use our site for any commercial\n    or\
  \ business purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openexchangerates/eligibility/openexchangerates-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Open Exchange Rates's own page on 2026-11-10.
synthetic: false
tags:
- Foreign Exchange
- Currency
- Exchange Rates
- Currency Conversion
- Financial Data
---
