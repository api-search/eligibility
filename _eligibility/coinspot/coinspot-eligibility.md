---
api_specs:
- filename: coinspot-public-api-api-openapi.yml
  format: yaml
  label: CoinSpot Public API
  slug: coinspot-public-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinspot/openapi/coinspot-public-api-api-openapi.yml
- filename: coinspot-read-only-api-api-openapi.yml
  format: yaml
  label: CoinSpot Read Only API
  slug: coinspot-read-only-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinspot/openapi/coinspot-read-only-api-api-openapi.yml
- filename: coinspot-trading-api-api-openapi.yml
  format: yaml
  label: CoinSpot Trading API
  slug: coinspot-trading-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinspot/openapi/coinspot-trading-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Our Platform and Services have been designed for Australian residents and are not intended to be offered or made available to any person who resides outside of Australia.
  entity_types:
  - text: personal, business and self-managed superfund CoinSpot accounts
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Criminal or restricted activities
    text: 'Engage in any restricted or criminal activities, including but not limited to: Terrorist financing; Money laundering; Illegal gambling'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: By creating a CoinSpot account, you authorise CoinSpot to make enquiries to verify your identity either directly or through third parties
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CoinSpot
provenance_date: '2026-11-09'
provider_name: CoinSpot
provider_slug: coinspot
slug: coinspot-eligibility
source_date: '2026-11-09'
source_filename: coinspot-eligibility.yml
source_heading: Eligibility
source_page: https://www.coinspot.com.au/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoinSpot\naid: coinspot\nurl: https://www.coinspot.com.au/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Our Platform and Services have been designed for Australian residents and are not intended to be offered\n    or made available to any person who resides outside of Australia.\nentity_types:\n- type: business\n  text: personal, business and self-managed superfund CoinSpot accounts\nrestricted_uses:\n- summary: Criminal or restricted activities\n  text: 'Engage in any restricted or criminal activities, including but not limited to: Terrorist financing; Money\n    laundering;\
  \ Illegal gambling'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: By creating a CoinSpot account, you authorise CoinSpot to make enquiries to verify your identity either\n    directly or through third parties\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coinspot/eligibility/coinspot-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from CoinSpot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Australia
- Bitcoin
- Market Data
---
