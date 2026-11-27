---
api_specs:
- filename: marketdata-app-indices-api-openapi.yml
  format: yaml
  label: Market Data Indices API
  slug: marketdata-app-indices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketdata-app/openapi/marketdata-app-indices-api-openapi.yml
- filename: marketdata-app-markets-api-openapi.yml
  format: yaml
  label: Market Data Markets API
  slug: marketdata-app-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketdata-app/openapi/marketdata-app-markets-api-openapi.yml
- filename: marketdata-app-options-api-openapi.yml
  format: yaml
  label: Market Data Options API
  slug: marketdata-app-options-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketdata-app/openapi/marketdata-app-options-api-openapi.yml
- filename: marketdata-app-stocks-api-openapi.yml
  format: yaml
  label: Market Data Stocks API
  slug: marketdata-app-stocks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/marketdata-app/openapi/marketdata-app-stocks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any company, organization, or corporate entity wishing to create an account must enter into a separate commercial agreement with us.
    type: business
  - text: Users of our self-service plans are limited to non-professional individuals only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Professional/commercial data resellers
    text: If you are in the business of selling, distributing, or licensing financial data to others, you may not use our services.
  - summary: Investment advice reliance
    text: You should not rely on this data as the sole basis for making trading or investment decisions.
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
name: Market Data
provenance_date: '2026-11-10'
provider_name: Market Data
provider_slug: marketdata-app
slug: marketdata-app-eligibility
source_date: '2026-11-10'
source_filename: marketdata-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.marketdata.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Market Data\naid: marketdata-app\nurl: https://www.marketdata.app/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Any company, organization, or corporate entity wishing to create an account must enter into a separate commercial\n    agreement with us.\n- type: individual\n  text: Users of our self-service plans are limited to non-professional individuals only.\nrestricted_uses:\n- summary: Professional/commercial data resellers\n  text: If you are in the business of selling, distributing, or licensing financial data to others,\
  \ you may not\n    use our services.\n- summary: Investment advice reliance\n  text: You should not rely on this data as the sole basis for making trading or investment decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/marketdata-app/eligibility/marketdata-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Market Data's own page on 2026-11-10.
synthetic: false
tags:
- Market Data
- Financial Data
- Stocks
- Options
- Indices
- Real-Time Data
- Historical Data
- Quotes
---
