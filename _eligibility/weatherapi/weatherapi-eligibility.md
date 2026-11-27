---
api_specs:
- filename: weatherapi-alerts-api-openapi.yml
  format: yaml
  label: WeatherAPI Alerts API
  slug: weatherapi-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-alerts-api-openapi.yml
- filename: weatherapi-future-api-openapi.yml
  format: yaml
  label: WeatherAPI Future API
  slug: weatherapi-future-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-future-api-openapi.yml
- filename: weatherapi-geo-api-openapi.yml
  format: yaml
  label: WeatherAPI Geo API
  slug: weatherapi-geo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-geo-api-openapi.yml
- filename: weatherapi-history-api-openapi.yml
  format: yaml
  label: WeatherAPI History API
  slug: weatherapi-history-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-history-api-openapi.yml
- filename: weatherapi-marine-api-openapi.yml
  format: yaml
  label: WeatherAPI Marine API
  slug: weatherapi-marine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-marine-api-openapi.yml
- filename: weatherapi-sports-api-openapi.yml
  format: yaml
  label: WeatherAPI Sports API
  slug: weatherapi-sports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-sports-api-openapi.yml
- filename: weatherapi-weather-api-openapi.yml
  format: yaml
  label: WeatherAPI Weather API
  slug: weatherapi-weather-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherapi/openapi/weatherapi-weather-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: sold or resold by you or your group companies or other third parties authorised by you
    type: business
  minimum_age:
    text: You represent that you are 16 years of age or older, of legal age to enter into contracts
    value: '16'
  restricted_uses:
  - summary: Illegal activity
    text: Using the API in any application or service that facilitates illegal activity.
  - summary: Safety-critical sole data source
    text: Using the data in any safety-critical system as the sole data source without independent verification against official meteorological services.
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
name: WeatherAPI
provenance_date: '2026-11-10'
provider_name: WeatherAPI
provider_slug: weatherapi
slug: weatherapi-eligibility
source_date: '2026-11-10'
source_filename: weatherapi-eligibility.yml
source_heading: Eligibility
source_page: https://www.weatherapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WeatherAPI\naid: weatherapi\nurl: https://www.weatherapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: sold or resold by you or your group companies or other third parties authorised by you\nrestricted_uses:\n- summary: Illegal activity\n  text: Using the API in any application or service that facilitates illegal activity.\n- summary: Safety-critical sole data source\n  text: Using the data in any safety-critical system as the sole data source without independent verification against\n    official meteorological services.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You represent that you are 16 years of age or older, of legal age to enter into contracts\n"
source_yaml_url: https://artifacts.apis.io/weatherapi/eligibility/weatherapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from WeatherAPI's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Forecast
- History
- Marine
- Astronomy
- Geolocation
- Sports
- Alerts
- Public APIs
---
