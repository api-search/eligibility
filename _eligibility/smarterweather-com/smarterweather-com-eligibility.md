---
api_specs:
- filename: smarterweather-com-agriculture-api-openapi.yml
  format: yaml
  label: smarterweather-com Agriculture API
  slug: smarterweather-com-agriculture-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-agriculture-api-openapi.yml
- filename: smarterweather-com-alerts-api-openapi.yml
  format: yaml
  label: smarterweather-com Alerts API
  slug: smarterweather-com-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-alerts-api-openapi.yml
- filename: smarterweather-com-climate-api-openapi.yml
  format: yaml
  label: smarterweather-com Climate API
  slug: smarterweather-com-climate-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-climate-api-openapi.yml
- filename: smarterweather-com-geocode-api-openapi.yml
  format: yaml
  label: smarterweather-com Geocode API
  slug: smarterweather-com-geocode-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-geocode-api-openapi.yml
- filename: smarterweather-com-guidance-api-openapi.yml
  format: yaml
  label: smarterweather-com Guidance API
  slug: smarterweather-com-guidance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-guidance-api-openapi.yml
- filename: smarterweather-com-health-api-openapi.yml
  format: yaml
  label: smarterweather-com Health API
  slug: smarterweather-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-health-api-openapi.yml
- filename: smarterweather-com-meta-api-openapi.yml
  format: yaml
  label: smarterweather-com Meta API
  slug: smarterweather-com-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-meta-api-openapi.yml
- filename: smarterweather-com-observations-api-openapi.yml
  format: yaml
  label: smarterweather-com Observations API
  slug: smarterweather-com-observations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-observations-api-openapi.yml
- filename: smarterweather-com-products-api-openapi.yml
  format: yaml
  label: smarterweather-com Products API
  slug: smarterweather-com-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-products-api-openapi.yml
- filename: smarterweather-com-storms-api-openapi.yml
  format: yaml
  label: smarterweather-com Storms API
  slug: smarterweather-com-storms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-storms-api-openapi.yml
- filename: smarterweather-com-weather-api-openapi.yml
  format: yaml
  label: smarterweather-com Weather API
  slug: smarterweather-com-weather-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/smarterweather-com/openapi/smarterweather-com-weather-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Smarter Weather covers the 50 US states and DC only.
  entity_types:
  - text: grants you a personal, non-commercial, non-exclusive licence to access and use the Service for your own weather information needs.
    type: individual
  - text: Commercial use of the Service or its data is permitted only (a) under a paid developer plan or a keyless x402 payment
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Life-safety-critical deployments
    text: use in life-safety-critical deployments without independent verification are prohibited.
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
name: smarterweather-com
provenance_date: '2026-11-10'
provider_name: smarterweather-com
provider_slug: smarterweather-com
slug: smarterweather-com-eligibility
source_date: '2026-11-10'
source_filename: smarterweather-com-eligibility.yml
source_heading: Eligibility
source_page: https://smarterweather.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: smarterweather-com\naid: smarterweather-com\nurl: https://smarterweather.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Smarter Weather covers the 50 US states and DC only.\nentity_types:\n- type: individual\n  text: grants you a personal, non-commercial, non-exclusive licence to access and use the Service for your own\n    weather information needs.\n- type: business\n  text: Commercial use of the Service or its data is permitted only (a) under a paid developer plan or a keyless\n    x402 payment\nrestricted_uses:\n- summary: Life-safety-critical deployments\n \
  \ text: use in life-safety-critical deployments without independent verification are prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/smarterweather-com/eligibility/smarterweather-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from smarterweather-com's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Weather
- Data
- Forecasting
- Climate
---
