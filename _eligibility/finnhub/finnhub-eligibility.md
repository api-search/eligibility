---
api_specs:
- filename: finnhub-default-api-openapi.yml
  format: yaml
  label: Finnhub Default API
  slug: finnhub-default-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/finnhub/openapi/finnhub-default-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your signature if signed up as for personal use will be used in the form Subscriber Agreement to certify that you are Non-Professional individual subscriber.
    type: individual
  - text: You are using this data for your business or registering under your business name regardless of the industry
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Securities professionals excluded from personal plans
    text: You are securities professional (registered with FINRA, SEC, CFTC or relevant regulatory bodies)
  - summary: Business use excluded from personal plans
    text: You are using this data for your business or registering under your business name regardless of the industry
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
name: Finnhub
provenance_date: '2026-11-09'
provider_name: Finnhub
provider_slug: finnhub
slug: finnhub-eligibility
source_date: '2026-11-09'
source_filename: finnhub-eligibility.yml
source_heading: Eligibility
source_page: https://finnhub.io/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Finnhub\naid: finnhub\nurl: https://finnhub.io/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Your signature if signed up as for personal use will be used in the form Subscriber Agreement to certify\n    that you are Non-Professional individual subscriber.\n- type: business\n  text: You are using this data for your business or registering under your business name regardless of the industry\nrestricted_uses:\n- summary: Securities professionals excluded from personal plans\n  text: You are securities professional (registered\
  \ with FINRA, SEC, CFTC or relevant regulatory bodies)\n- summary: Business use excluded from personal plans\n  text: You are using this data for your business or registering under your business name regardless of the industry\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/finnhub/eligibility/finnhub-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Finnhub's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Stocks
- Foreign Exchange
- Cryptocurrency
- Fundamentals
- News
- WebSocket
- Real-Time
- Financial Data
---
