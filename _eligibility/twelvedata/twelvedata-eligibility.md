---
api_specs:
- filename: twelvedata-asyncapi.yml
  format: yaml
  label: Twelve Data WebSocket Streaming API
  slug: twelvedata-websocket-streaming-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/twelvedata/asyncapi/twelvedata-asyncapi.yml
- filename: twelvedata-core-data-api-openapi.yml
  format: yaml
  label: Twelve Data Core Data API
  slug: twelvedata-core-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-core-data-api-openapi.yml
- filename: twelvedata-fundamentals-api-openapi.yml
  format: yaml
  label: Twelve Data Fundamentals API
  slug: twelvedata-fundamentals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-fundamentals-api-openapi.yml
- filename: twelvedata-reference-data-api-openapi.yml
  format: yaml
  label: Twelve Data Reference Data API
  slug: twelvedata-reference-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-reference-data-api-openapi.yml
- filename: twelvedata-technical-indicators-api-openapi.yml
  format: yaml
  label: Twelve Data Technical Indicators API
  slug: twelvedata-technical-indicators-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-technical-indicators-api-openapi.yml
- filename: twelvedata-time-series-api-openapi.yml
  format: yaml
  label: Twelve Data Time Series API
  slug: twelvedata-time-series-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-time-series-api-openapi.yml
- filename: twelvedata-advanced-api-openapi.yml
  format: yaml
  label: Twelve Data Advanced API
  slug: twelvedata-advanced-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-advanced-api-openapi.yml
- filename: twelvedata-analysis-api-openapi.yml
  format: yaml
  label: Twelve Data Analysis API
  slug: twelvedata-analysis-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-analysis-api-openapi.yml
- filename: twelvedata-currencies-api-openapi.yml
  format: yaml
  label: Twelve Data Currencies API
  slug: twelvedata-currencies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-currencies-api-openapi.yml
- filename: twelvedata-market-data-api-openapi.yml
  format: yaml
  label: Twelve Data Market Data API
  slug: twelvedata-market-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-market-data-api-openapi.yml
- filename: twelvedata-money-market-funds-api-openapi.yml
  format: yaml
  label: Twelve Data Money Market Funds API
  slug: twelvedata-money-market-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-money-market-funds-api-openapi.yml
- filename: twelvedata-mutual-funds-api-openapi.yml
  format: yaml
  label: Twelve Data Mutual Funds API
  slug: twelvedata-mutual-funds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-mutual-funds-api-openapi.yml
- filename: twelvedata-regulatory-api-openapi.yml
  format: yaml
  label: Twelve Data Regulatory API
  slug: twelvedata-regulatory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-regulatory-api-openapi.yml
- filename: twelvedata-technical-indicator-api-openapi.yml
  format: yaml
  label: Twelve Data Technical Indicator API
  slug: twelvedata-technical-indicator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-technical-indicator-api-openapi.yml
- filename: twelvedata-etfs-api-openapi.yml
  format: yaml
  label: Twelve Data Etfs API
  slug: twelvedata-etfs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/twelvedata/openapi/twelvedata-etfs-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: whether as an individual or on behalf of an entity you represent
    type: individual
  - text: If you are accepting this Agreement on behalf of a legal entity, you represent and warrant that you have full legal authority to bind that entity to this Agreement.
    type: business
  minimum_age:
    text: If you do not have this authority, are under 18 years of age, or do not agree with this Agreement, you must not accept these terms and may not access or use the Platform.
    value: '18'
  restricted_uses:
  - summary: Non-display and high-frequency trading
    text: Use data for high-frequency trading without appropriate license
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
name: Twelve Data
provenance_date: '2026-11-10'
provider_name: Twelve Data
provider_slug: twelvedata
slug: twelvedata-eligibility
source_date: '2026-11-10'
source_filename: twelvedata-eligibility.yml
source_heading: Eligibility
source_page: https://twelvedata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Twelve Data\naid: twelvedata\nurl: https://twelvedata.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: whether as an individual or on behalf of an entity you represent\n- type: business\n  text: If you are accepting this Agreement on behalf of a legal entity, you represent and warrant that you have\n    full legal authority to bind that entity to this Agreement.\nrestricted_uses:\n- summary: Non-display and high-frequency trading\n  text: Use data for high-frequency trading without appropriate license\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you do not have this authority, are under 18 years of age, or do not agree with this Agreement, you must\n    not accept these terms and may not access or use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/twelvedata/eligibility/twelvedata-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Twelve Data's own page on 2026-11-10.
synthetic: false
tags:
- Market Data
- Financial Data
- Stocks
- Foreign Exchange
- Cryptocurrency
- Real-Time Data
- Technical Indicators
- Fundamentals
- Real-Time
---
