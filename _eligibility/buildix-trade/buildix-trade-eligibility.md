---
api_specs:
- filename: buildix-trade-deep-view-api-openapi.yml
  format: yaml
  label: Buildix Deep View API
  slug: buildix-trade-deep-view-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-deep-view-api-openapi.yml
- filename: buildix-trade-funding-arb-api-openapi.yml
  format: yaml
  label: Buildix Funding Arb API
  slug: buildix-trade-funding-arb-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-funding-arb-api-openapi.yml
- filename: buildix-trade-pair-api-openapi.yml
  format: yaml
  label: Buildix Pair API
  slug: buildix-trade-pair-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-pair-api-openapi.yml
- filename: buildix-trade-screener-api-openapi.yml
  format: yaml
  label: Buildix Screener API
  slug: buildix-trade-screener-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-screener-api-openapi.yml
- filename: buildix-trade-signals-api-openapi.yml
  format: yaml
  label: Buildix Signals API
  slug: buildix-trade-signals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-signals-api-openapi.yml
- filename: buildix-trade-smart-money-api-openapi.yml
  format: yaml
  label: Buildix Smart Money API
  slug: buildix-trade-smart-money-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/buildix-trade/openapi/buildix-trade-smart-money-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Service is not available in jurisdictions where cryptocurrency trading analytics services are prohibited.
  entity_types:
  - text: You must be at least 18 years old and legally able to enter into a binding contract in your jurisdiction.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally able to enter into a binding contract in your jurisdiction.
    value: '18'
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
name: Buildix
provenance_date: '2026-11-09'
provider_name: Buildix
provider_slug: buildix-trade
slug: buildix-trade-eligibility
source_date: '2026-11-09'
source_filename: buildix-trade-eligibility.yml
source_heading: Eligibility
source_page: https://www.buildix.trade/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Buildix\naid: buildix-trade\nurl: https://www.buildix.trade/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Service is not available in jurisdictions where cryptocurrency trading analytics services are prohibited.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally able to enter into a binding contract in your jurisdiction.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally able to enter into\
  \ a binding contract in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/buildix-trade/eligibility/buildix-trade-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Buildix's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Analytics
- Orderflow
- Artificial Intelligence
---
