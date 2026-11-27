---
api_specs:
- filename: delta-exchange-assets-api-openapi.yml
  format: yaml
  label: Delta Exchange Assets API
  slug: delta-exchange-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delta-exchange/openapi/delta-exchange-assets-api-openapi.yml
- filename: delta-exchange-heartbeat-management-api-openapi.yml
  format: yaml
  label: Delta Exchange Heartbeat Management API
  slug: delta-exchange-heartbeat-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delta-exchange/openapi/delta-exchange-heartbeat-management-api-openapi.yml
- filename: delta-exchange-orderbook-api-openapi.yml
  format: yaml
  label: Delta Exchange Orderbook API
  slug: delta-exchange-orderbook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delta-exchange/openapi/delta-exchange-orderbook-api-openapi.yml
- filename: delta-exchange-orders-api-openapi.yml
  format: yaml
  label: Delta Exchange Orders API
  slug: delta-exchange-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delta-exchange/openapi/delta-exchange-orders-api-openapi.yml
- filename: delta-exchange-positions-api-openapi.yml
  format: yaml
  label: Delta Exchange Positions API
  slug: delta-exchange-positions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delta-exchange/openapi/delta-exchange-positions-api-openapi.yml
- filename: delta-exchange-products-api-openapi.yml
  format: yaml
  label: Delta Exchange Products API
  slug: delta-exchange-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delta-exchange/openapi/delta-exchange-products-api-openapi.yml
- filename: delta-exchange-wallet-api-openapi.yml
  format: yaml
  label: Delta Exchange Wallet API
  slug: delta-exchange-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delta-exchange/openapi/delta-exchange-wallet-api-openapi.yml
- filename: delta-exchange-ohlc-candles-api-openapi.yml
  format: yaml
  label: Delta Exchange OHLC Candles API
  slug: delta-exchange-ohlc-candles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delta-exchange/openapi/delta-exchange-ohlc-candles-api-openapi.yml
- filename: delta-exchange-trade-history-api-openapi.yml
  format: yaml
  label: Delta Exchange Trade History API
  slug: delta-exchange-trade-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/delta-exchange/openapi/delta-exchange-trade-history-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: The Services and access to the Platform are available only to eligible natural persons and legal entities that are residents of India in accordance with Applicable Law.
  entity_types:
  - text: If you are an individual user, to be eligible to open an Individual Account, you must satisfy all the following eligibility criteria
    type: individual
  - text: If you are an Institutional user, to be eligible to open a Corporate Account, you must satisfy all the following eligibility criteria
    type: business
  minimum_age:
    text: you are of legal age to form a binding contract (i.e. at 18 (eighteen) years of age or above)
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to access and use certain Services (including the Exchange and the Platform), you will need to have an Account by submitting the details requested in our Account creation form.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Delta Exchange
provenance_date: '2026-11-09'
provider_name: Delta Exchange
provider_slug: delta-exchange
slug: delta-exchange-eligibility
source_date: '2026-11-09'
source_filename: delta-exchange-eligibility.yml
source_heading: Eligibility
source_page: https://www.delta.exchange/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Delta Exchange\naid: delta-exchange\nurl: https://www.delta.exchange/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: The Services and access to the Platform are available only to eligible natural persons and legal entities\n    that are residents of India in accordance with Applicable Law.\nentity_types:\n- type: individual\n  text: If you are an individual user, to be eligible to open an Individual Account, you must satisfy all the following\n    eligibility criteria\n- type: business\n  text: If you are an Institutional user, to be eligible\
  \ to open a Corporate Account, you must satisfy all the following\n    eligibility criteria\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to access and use certain Services (including the Exchange and the Platform), you will need to\n    have an Account by submitting the details requested in our Account creation form.\nminimum_age:\n  value: '18'\n  text: you are of legal age to form a binding contract (i.e. at 18 (eighteen) years of age or above)\n"
source_yaml_url: https://artifacts.apis.io/delta-exchange/eligibility/delta-exchange-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from Delta Exchange's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Crypto Exchanges
- Derivatives
- Trading
- Options
- Futures
- Market Data
---
