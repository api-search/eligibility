---
api_specs:
- filename: patternfetch-com-api-openapi.json
  format: json
  label: patternfetch Api API
  slug: patternfetch-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/patternfetch-com/openapi/_original/patternfetch-com-api-openapi.json
claim_count: 2
description: ''
doc:
  countries:
    excluded:
    - US
    served: []
    text: Crypto-asset data is not offered or delivered to US persons or to requests originating from the United States; such requests are refused by the Service. Stock and ETF data is not subject to this restriction.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not investment advice
    text: Nothing on the Service is a recommendation, solicitation, inducement, or offer to buy, sell, or hold any security, exchange-traded fund, crypto-asset or other instrument, or to adopt any strategy.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: patternfetch-com
provenance_date: '2026-11-10'
provider_name: patternfetch-com
provider_slug: patternfetch-com
slug: patternfetch-com-eligibility
source_date: '2026-11-10'
source_filename: patternfetch-com-eligibility.yml
source_heading: Eligibility
source_page: https://patternfetch.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: patternfetch-com\naid: patternfetch-com\nurl: https://patternfetch.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  text: Crypto-asset data is not offered or delivered to US persons or to requests originating from the United States;\n    such requests are refused by the Service. Stock and ETF data is not subject to this restriction.\nentity_types: []\nrestricted_uses:\n- summary: Not investment advice\n  text: Nothing on the Service is a recommendation, solicitation, inducement, or offer to buy, sell, or hold any\n    security, exchange-traded fund, crypto-asset or other\
  \ instrument, or to adopt any strategy.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/patternfetch-com/eligibility/patternfetch-com-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from patternfetch-com's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Market Data
- Stocks
- Cryptocurrency
---
