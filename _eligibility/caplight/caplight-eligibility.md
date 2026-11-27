---
api_specs:
- filename: caplight-companies-api-openapi.yml
  format: yaml
  label: Caplight Companies API
  slug: caplight-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-companies-api-openapi.yml
- filename: caplight-company-api-openapi.yml
  format: yaml
  label: Caplight Company API
  slug: caplight-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-company-api-openapi.yml
- filename: caplight-company-details-api-openapi.yml
  format: yaml
  label: Caplight Company Details API
  slug: caplight-company-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-company-details-api-openapi.yml
- filename: caplight-company-filings-api-openapi.yml
  format: yaml
  label: Caplight Company Filings API
  slug: caplight-company-filings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-company-filings-api-openapi.yml
- filename: caplight-company-lookup-api-openapi.yml
  format: yaml
  label: Caplight Company Lookup API
  slug: caplight-company-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-company-lookup-api-openapi.yml
- filename: caplight-composite-index-api-openapi.yml
  format: yaml
  label: Caplight Composite Index API
  slug: caplight-composite-index-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-composite-index-api-openapi.yml
- filename: caplight-comps-api-openapi.yml
  format: yaml
  label: Caplight Comps API
  slug: caplight-comps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-comps-api-openapi.yml
- filename: caplight-fund-marks-api-openapi.yml
  format: yaml
  label: Caplight Fund Marks API
  slug: caplight-fund-marks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-fund-marks-api-openapi.yml
- filename: caplight-funding-rounds-api-openapi.yml
  format: yaml
  label: Caplight Funding Rounds API
  slug: caplight-funding-rounds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-funding-rounds-api-openapi.yml
- filename: caplight-investors-api-openapi.yml
  format: yaml
  label: Caplight Investors API
  slug: caplight-investors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-investors-api-openapi.yml
- filename: caplight-live-orderbook-api-openapi.yml
  format: yaml
  label: Caplight Live Orderbook API
  slug: caplight-live-orderbook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-live-orderbook-api-openapi.yml
- filename: caplight-news-api-openapi.yml
  format: yaml
  label: Caplight News API
  slug: caplight-news-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-news-api-openapi.yml
- filename: caplight-order-history-api-openapi.yml
  format: yaml
  label: Caplight Order History API
  slug: caplight-order-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-order-history-api-openapi.yml
- filename: caplight-stock-splits-api-openapi.yml
  format: yaml
  label: Caplight Stock Splits API
  slug: caplight-stock-splits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-stock-splits-api-openapi.yml
- filename: caplight-trade-history-api-openapi.yml
  format: yaml
  label: Caplight Trade History API
  slug: caplight-trade-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-trade-history-api-openapi.yml
- filename: caplight-market-price-api-openapi.yml
  format: yaml
  label: Caplight Market Price API
  slug: caplight-market-price-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/caplight/openapi/caplight-market-price-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is available only to individuals who are at least 18 years old.
    type: individual
  minimum_age:
    text: The Service is available only to individuals who are at least 18 years old.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Caplight may, in its sole discretion, refuse to offer the Service to any person or entity and change its eligibility criteria at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Caplight
provenance_date: '2026-11-09'
provider_name: Caplight
provider_slug: caplight
slug: caplight-eligibility
source_date: '2026-11-09'
source_filename: caplight-eligibility.yml
source_heading: Eligibility
source_page: https://www.caplight.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Caplight\naid: caplight\nurl: https://www.caplight.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who are at least 18 years old.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Caplight may, in its sole discretion, refuse to offer the Service to any person or entity and change its\n    eligibility criteria at any time.\nminimum_age:\n  value: '18'\n  text: The Service is available only to individuals who are at least\
  \ 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/caplight/eligibility/caplight-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Caplight's own page on 2026-11-09.
synthetic: false
tags:
- Private Markets
- Secondary Market
- Market Data
- Venture Capital
- Company Data
- investor-data
- Funding Rounds
- Pricing Data
- Financial Data
- Fintech
- MCP
- Agent-Native
---
