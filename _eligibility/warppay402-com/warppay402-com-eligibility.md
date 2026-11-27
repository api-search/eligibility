---
api_specs:
- filename: warppay402-com-feeds-api-openapi.yml
  format: yaml
  label: WarpPay402 Studio Feeds API
  slug: warppay402-com-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warppay402-com/openapi/warppay402-com-feeds-api-openapi.yml
- filename: warppay402-com-public-data-feed-api-openapi.yml
  format: yaml
  label: WarpPay402 Studio Public Data Feed API
  slug: warppay402-com-public-data-feed-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warppay402-com/openapi/warppay402-com-public-data-feed-api-openapi.yml
- filename: warppay402-com-tools-api-openapi.yml
  format: yaml
  label: WarpPay402 Studio Tools API
  slug: warppay402-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/warppay402-com/openapi/warppay402-com-tools-api-openapi.yml
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
  - summary: Sanctioned persons
    text: Access to all API endpoints, account abstraction paymasters, and DeFi routing engines is strictly prohibited for any individual, organization, or digital currency wallet designated under economic or trade sanctions.
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
name: WarpPay402 Studio
provenance_date: '2026-11-10'
provider_name: WarpPay402 Studio
provider_slug: warppay402-com
slug: warppay402-com-eligibility
source_date: '2026-11-10'
source_filename: warppay402-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.warppay402.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WarpPay402 Studio\naid: warppay402-com\nurl: https://www.warppay402.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned persons\n  text: Access to all API endpoints, account abstraction paymasters, and DeFi routing engines is strictly prohibited\n    for any individual, organization, or digital currency wallet designated under economic or trade sanctions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/warppay402-com/eligibility/warppay402-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from WarpPay402 Studio's own page on 2026-11-10.
synthetic: false
tags:
- x402
- Micropayments
- AI Agents
- MCP
- A2A
- Agent-Native
- Web Scraping
- Data Extraction
- Blockchain
- DeFi
- Base
- Solana
- Smart Contracts
- Data Feed
- Developer Tools
---
