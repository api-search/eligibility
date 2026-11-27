---
api_specs:
- filename: weatherbit-16-day-daily-forecast-api-openapi.yml
  format: yaml
  label: Weatherbit 16 Day / Daily Forecast API
  slug: weatherbit-16-day-daily-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-16-day-daily-forecast-api-openapi.yml
- filename: weatherbit-240-hour-hourly-forecast-api-openapi.yml
  format: yaml
  label: Weatherbit 240 Hour / Hourly Forecast API
  slug: weatherbit-240-hour-hourly-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-240-hour-hourly-forecast-api-openapi.yml
- filename: weatherbit-60-minute-rain-snow-nowcast-api-openapi.yml
  format: yaml
  label: Weatherbit 60 Minute Rain/Snow Nowcast API
  slug: weatherbit-60-minute-rain-snow-nowcast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-60-minute-rain-snow-nowcast-api-openapi.yml
- filename: weatherbit-agweather-forecast-api-openapi.yml
  format: yaml
  label: Weatherbit AgWeather Forecast API
  slug: weatherbit-agweather-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-agweather-forecast-api-openapi.yml
- filename: weatherbit-air-quality-forecast-api-openapi.yml
  format: yaml
  label: Weatherbit Air Quality Forecast API
  slug: weatherbit-air-quality-forecast-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-air-quality-forecast-api-openapi.yml
- filename: weatherbit-alerts-api-openapi.yml
  format: yaml
  label: Weatherbit Alerts API
  slug: weatherbit-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-alerts-api-openapi.yml
- filename: weatherbit-bulk-downloads-api-openapi.yml
  format: yaml
  label: Weatherbit Bulk Downloads API
  slug: weatherbit-bulk-downloads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-bulk-downloads-api-openapi.yml
- filename: weatherbit-climate-normals-averages-api-openapi.yml
  format: yaml
  label: Weatherbit Climate Normals (Averages) API
  slug: weatherbit-climate-normals-averages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-climate-normals-averages-api-openapi.yml
- filename: weatherbit-current-air-quality-api-openapi.yml
  format: yaml
  label: Weatherbit Current Air Quality API
  slug: weatherbit-current-air-quality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-current-air-quality-api-openapi.yml
- filename: weatherbit-current-weather-data-api-openapi.yml
  format: yaml
  label: Weatherbit Current Weather Data API
  slug: weatherbit-current-weather-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-current-weather-data-api-openapi.yml
- filename: weatherbit-daily-historical-weather-data-api-openapi.yml
  format: yaml
  label: Weatherbit Daily Historical Weather Data API
  slug: weatherbit-daily-historical-weather-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-daily-historical-weather-data-api-openapi.yml
- filename: weatherbit-forecast-degree-day-api-api-openapi.yml
  format: yaml
  label: Weatherbit Forecast Degree Day API
  slug: weatherbit-forecast-degree-day-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-forecast-degree-day-api-api-openapi.yml
- filename: weatherbit-historical-agweather-data-api-openapi.yml
  format: yaml
  label: Weatherbit Historical AgWeather Data API
  slug: weatherbit-historical-agweather-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-historical-agweather-data-api-openapi.yml
- filename: weatherbit-historical-air-quality-api-openapi.yml
  format: yaml
  label: Weatherbit Historical Air Quality API
  slug: weatherbit-historical-air-quality-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-historical-air-quality-api-openapi.yml
- filename: weatherbit-historical-degree-day-api-api-openapi.yml
  format: yaml
  label: Weatherbit Historical Degree Day API
  slug: weatherbit-historical-degree-day-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-historical-degree-day-api-api-openapi.yml
- filename: weatherbit-hourly-historical-weather-data-api-openapi.yml
  format: yaml
  label: Weatherbit Hourly Historical Weather Data API
  slug: weatherbit-hourly-historical-weather-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-hourly-historical-weather-data-api-openapi.yml
- filename: weatherbit-sub-hourly-historical-weather-data-api-openapi.yml
  format: yaml
  label: Weatherbit Sub-Hourly Historical Weather Data API
  slug: weatherbit-sub-hourly-historical-weather-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/weatherbit/openapi/weatherbit-sub-hourly-historical-weather-data-api-openapi.yml
claim_count: 3
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
  - summary: Mission critical applications
    text: Use of our API for mission critical applications. This includes any service where failure will lead to personal injury, death, or environmental damage.
  - summary: Advertising use of free tier
    text: Use of our Free tier API to target or trigger advertising.
  - summary: Commercial use of free tier
    text: Commercial use of our Free/trial/hobbyist tier API.
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
name: Weatherbit
provenance_date: '2026-11-10'
provider_name: Weatherbit
provider_slug: weatherbit
slug: weatherbit-eligibility
source_date: '2026-11-10'
source_filename: weatherbit-eligibility.yml
source_heading: Eligibility
source_page: https://www.weatherbit.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Weatherbit\naid: weatherbit\nurl: https://www.weatherbit.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Mission critical applications\n  text: Use of our API for mission critical applications. This includes any service where failure will lead to personal\n    injury, death, or environmental damage.\n- summary: Advertising use of free tier\n  text: Use of our Free tier API to target or trigger advertising.\n- summary: Commercial use of free tier\n  text: Commercial use of our Free/trial/hobbyist tier API.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/weatherbit/eligibility/weatherbit-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 3 quoted statements, read from Weatherbit's own page on 2026-11-10.
synthetic: false
tags:
- Weather
- Forecasting
- Historical Data
- Air Quality
- Alerts
- Agricultural Weather
---
