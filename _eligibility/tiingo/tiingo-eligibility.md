---
api_specs:
- filename: tiingo-boats-api-openapi.yml
  format: yaml
  label: Tiingo BOATS API
  slug: tiingo-boats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-boats-api-openapi.yml
- filename: tiingo-corporate-actions-api-openapi.yml
  format: yaml
  label: Tiingo Corporate Actions API
  slug: tiingo-corporate-actions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-corporate-actions-api-openapi.yml
- filename: tiingo-crypto-api-openapi.yml
  format: yaml
  label: Tiingo Crypto API
  slug: tiingo-crypto-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-crypto-api-openapi.yml
- filename: tiingo-crypto-yield-api-openapi.yml
  format: yaml
  label: Tiingo Crypto Yield API
  slug: tiingo-crypto-yield-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-crypto-yield-api-openapi.yml
- filename: tiingo-end-of-day-api-openapi.yml
  format: yaml
  label: Tiingo End Of Day API
  slug: tiingo-end-of-day-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-end-of-day-api-openapi.yml
- filename: tiingo-equity-realtime-api-openapi.yml
  format: yaml
  label: Tiingo Equity Realtime API
  slug: tiingo-equity-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-equity-realtime-api-openapi.yml
- filename: tiingo-forex-api-openapi.yml
  format: yaml
  label: Tiingo Forex API
  slug: tiingo-forex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-forex-api-openapi.yml
- filename: tiingo-fund-fees-api-openapi.yml
  format: yaml
  label: Tiingo Fund Fees API
  slug: tiingo-fund-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-fund-fees-api-openapi.yml
- filename: tiingo-fundamentals-api-openapi.yml
  format: yaml
  label: Tiingo Fundamentals API
  slug: tiingo-fundamentals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-fundamentals-api-openapi.yml
- filename: tiingo-iex-api-openapi.yml
  format: yaml
  label: Tiingo IEX API
  slug: tiingo-iex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-iex-api-openapi.yml
- filename: tiingo-news-api-openapi.yml
  format: yaml
  label: Tiingo News API
  slug: tiingo-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-news-api-openapi.yml
- filename: tiingo-small-exchange-api-openapi.yml
  format: yaml
  label: Tiingo Small Exchange API
  slug: tiingo-small-exchange-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-small-exchange-api-openapi.yml
- filename: tiingo-utilities-api-openapi.yml
  format: yaml
  label: Tiingo Utilities API
  slug: tiingo-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tiingo/openapi/tiingo-utilities-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual, you may sign up for an Individual plan
    type: individual
  - text: if you are representing an organization or business, you must sign up for a Commercial plan
    type: business
  minimum_age:
    text: at least thirteen (13) years old
    value: '13'
  restricted_uses:
  - summary: AI training, generative AI and benchmarking require an Enterprise License
    text: Regardless of your subscription plan, the following uses require an Enterprise License, which must be in place before the use begins
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
name: Tiingo
provenance_date: '2026-11-10'
provider_name: Tiingo
provider_slug: tiingo
slug: tiingo-eligibility
source_date: '2026-11-10'
source_filename: tiingo-eligibility.yml
source_heading: Eligibility
source_page: https://www.tiingo.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tiingo\naid: tiingo\nurl: https://www.tiingo.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual, you may sign up for an Individual plan\n- type: business\n  text: if you are representing an organization or business, you must sign up for a Commercial plan\nrestricted_uses:\n- summary: AI training, generative AI and benchmarking require an Enterprise License\n  text: Regardless of your subscription plan, the following uses require an Enterprise License, which must be in\n    place before\
  \ the use begins\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: at least thirteen (13) years old\n"
source_yaml_url: https://artifacts.apis.io/tiingo/eligibility/tiingo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tiingo's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Market Data
- Stocks
- Cryptocurrency
- Foreign Exchange
- News
- Fundamentals
- WebSocket
- Real-Time
- Financial Data
---
