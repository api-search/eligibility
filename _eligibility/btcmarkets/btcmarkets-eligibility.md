---
api_specs:
- filename: btcmarkets-account-apis-api-openapi.yml
  format: yaml
  label: BTC Markets Account APIs API
  slug: btcmarkets-account-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btcmarkets/openapi/btcmarkets-account-apis-api-openapi.yml
- filename: btcmarkets-batch-order-apis-api-openapi.yml
  format: yaml
  label: BTC Markets Batch Order APIs API
  slug: btcmarkets-batch-order-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btcmarkets/openapi/btcmarkets-batch-order-apis-api-openapi.yml
- filename: btcmarkets-fund-management-apis-api-openapi.yml
  format: yaml
  label: BTC Markets Fund Management APIs API
  slug: btcmarkets-fund-management-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btcmarkets/openapi/btcmarkets-fund-management-apis-api-openapi.yml
- filename: btcmarkets-market-data-apis-api-openapi.yml
  format: yaml
  label: BTC Markets Market Data APIs API
  slug: btcmarkets-market-data-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btcmarkets/openapi/btcmarkets-market-data-apis-api-openapi.yml
- filename: btcmarkets-misc-apis-api-openapi.yml
  format: yaml
  label: BTC Markets Misc APIs API
  slug: btcmarkets-misc-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btcmarkets/openapi/btcmarkets-misc-apis-api-openapi.yml
- filename: btcmarkets-order-placement-apis-api-openapi.yml
  format: yaml
  label: BTC Markets Order Placement APIs API
  slug: btcmarkets-order-placement-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btcmarkets/openapi/btcmarkets-order-placement-apis-api-openapi.yml
- filename: btcmarkets-report-apis-api-openapi.yml
  format: yaml
  label: BTC Markets Report APIs API
  slug: btcmarkets-report-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btcmarkets/openapi/btcmarkets-report-apis-api-openapi.yml
- filename: btcmarkets-trade-apis-api-openapi.yml
  format: yaml
  label: BTC Markets Trade APIs API
  slug: btcmarkets-trade-apis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/btcmarkets/openapi/btcmarkets-trade-apis-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: be an Australian resident (except for Approved Overseas Users and Liquidity Providers accepted at our discretion)
  entity_types:
  - text: be an individual who is at least 18 years of age
    type: individual
  - text: a corporation, partnership, trust or other legal entity duly incorporated or established under the laws of its jurisdiction
    type: business
  minimum_age:
    text: be an individual who is at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Restricted persons or unlawful jurisdictions
    text: not be a Restricted Person or located in a jurisdiction where your use of the BTC Markets Services would breach any Applicable Law
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Before you are permitted to access and use the BTC Markets Services, you must comply with our identity verification ( Know Your Customer or KYC ) procedures
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BTC Markets
provenance_date: '2026-11-09'
provider_name: BTC Markets
provider_slug: btcmarkets
slug: btcmarkets-eligibility
source_date: '2026-11-09'
source_filename: btcmarkets-eligibility.yml
source_heading: Eligibility
source_page: https://www.btcmarkets.net/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BTC Markets\naid: btcmarkets\nurl: https://www.btcmarkets.net/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: be an Australian resident (except for Approved Overseas Users and Liquidity Providers accepted at our discretion)\nentity_types:\n- type: individual\n  text: be an individual who is at least 18 years of age\n- type: business\n  text: a corporation, partnership, trust or other legal entity duly incorporated or established under the laws\n    of its jurisdiction\nrestricted_uses:\n- summary: Restricted persons or unlawful jurisdictions\n\
  \  text: not be a Restricted Person or located in a jurisdiction where your use of the BTC Markets Services would\n    breach any Applicable Law\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Before you are permitted to access and use the BTC Markets Services, you must comply with our identity verification\n    ( Know Your Customer or KYC ) procedures\nminimum_age:\n  value: '18'\n  text: be an individual who is at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/btcmarkets/eligibility/btcmarkets-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from BTC Markets's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Exchange
- Trading
- Market Data
- Australia
---
