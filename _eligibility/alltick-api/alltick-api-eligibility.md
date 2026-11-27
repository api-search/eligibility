---
api_specs:
- filename: alltick-api-quote-b-api-api-openapi.yml
  format: yaml
  label: AllTick API Quote B API
  slug: alltick-api-quote-b-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alltick-api/openapi/alltick-api-quote-b-api-api-openapi.yml
- filename: alltick-api-quote-stock-b-api-api-openapi.yml
  format: yaml
  label: AllTick API Quote Stock B API
  slug: alltick-api-quote-stock-b-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alltick-api/openapi/alltick-api-quote-stock-b-api-api-openapi.yml
- filename: alltick-api-suspension-api-openapi.yml
  format: yaml
  label: AllTick API Suspension API
  slug: alltick-api-suspension-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alltick-api/openapi/alltick-api-suspension-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: individuals who are at least 18 years old or are considered fully competent to enter into contracts under applicable law
    type: individual
  - text: companies or other legal entities
    type: business
  minimum_age:
    text: at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Harm to AllTick or third parties
    text: Users agree not to engage in any activity that could harm the normal operation of AllTick or any third party through the use of the service.
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
name: AllTick API
provenance_date: '2026-11-09'
provider_name: AllTick API
provider_slug: alltick-api
slug: alltick-api-eligibility
source_date: '2026-11-09'
source_filename: alltick-api-eligibility.yml
source_heading: Eligibility
source_page: https://alltick.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AllTick API\naid: alltick-api\nurl: https://alltick.co/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: individuals who are at least 18 years old or are considered fully competent to enter into contracts under\n    applicable law\n- type: business\n  text: companies or other legal entities\nrestricted_uses:\n- summary: Harm to AllTick or third parties\n  text: Users agree not to engage in any activity that could harm the normal operation of AllTick or any third party\n    through the use of the service.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/alltick-api/eligibility/alltick-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AllTick API's own page on 2026-11-09.
synthetic: false
tags:
- Financial market data
- Real-Time Data
- stock-market-data
- forex-data
- Cryptocurrency Data
- commodities-data
- Tick Data
- WebSocket streaming
- Fintech
- Quantitative Trading
- Market Data API
- trading-halts
---
