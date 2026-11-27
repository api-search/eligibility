---
api_specs:
- filename: tickfeed-pro-account-api-openapi.yml
  format: yaml
  label: tickfeed-pro Account API
  slug: tickfeed-pro-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickfeed-pro/openapi/tickfeed-pro-account-api-openapi.yml
- filename: tickfeed-pro-market-data-api-openapi.yml
  format: yaml
  label: tickfeed-pro market data API
  slug: tickfeed-pro-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickfeed-pro/openapi/tickfeed-pro-market-data-api-openapi.yml
- filename: tickfeed-pro-system-api-openapi.yml
  format: yaml
  label: tickfeed-pro System API
  slug: tickfeed-pro-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tickfeed-pro/openapi/tickfeed-pro-system-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Some sections apply differently to consumers (individuals using the Service mainly outside their trade, business or profession).
    type: individual
  - text: If you use the Service for a business, you confirm you are authorised to accept these terms for it, and “you” includes that business.
    type: business
  minimum_age:
    text: You must be at least 18 and give accurate information, including a working email address.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: use the Service for anything unlawful, including market manipulation, fraud, or breaching sanctions;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: One account per person or business, unless we agree otherwise.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tickfeed-pro
provenance_date: '2026-11-10'
provider_name: tickfeed-pro
provider_slug: tickfeed-pro
slug: tickfeed-pro-eligibility
source_date: '2026-11-10'
source_filename: tickfeed-pro-eligibility.yml
source_heading: Eligibility
source_page: https://tickfeed.pro/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tickfeed-pro\naid: tickfeed-pro\nurl: https://tickfeed.pro/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Some sections apply differently to consumers (individuals using the Service mainly outside their trade,\n    business or profession).\n- type: business\n  text: If you use the Service for a business, you confirm you are authorised to accept these terms for it, and\n    “you” includes that business.\nrestricted_uses:\n- summary: Unlawful use\n  text: use the Service for anything unlawful, including market manipulation, fraud,\
  \ or breaching sanctions;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: One account per person or business, unless we agree otherwise.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and give accurate information, including a working email address.\n"
source_yaml_url: https://artifacts.apis.io/tickfeed-pro/eligibility/tickfeed-pro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from tickfeed-pro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Finance
- Market Data
- Foreign Exchange
- Gold
- MCP
---
