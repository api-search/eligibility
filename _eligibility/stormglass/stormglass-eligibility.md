---
api_specs:
- filename: stormglass-astronomy-api-openapi.yml
  format: yaml
  label: Stormglass Astronomy API
  slug: stormglass-astronomy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stormglass/openapi/stormglass-astronomy-api-openapi.yml
- filename: stormglass-bio-api-openapi.yml
  format: yaml
  label: Stormglass Bio API
  slug: stormglass-bio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stormglass/openapi/stormglass-bio-api-openapi.yml
- filename: stormglass-elevation-api-openapi.yml
  format: yaml
  label: Stormglass Elevation API
  slug: stormglass-elevation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stormglass/openapi/stormglass-elevation-api-openapi.yml
- filename: stormglass-marine-api-openapi.yml
  format: yaml
  label: Stormglass Marine API
  slug: stormglass-marine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stormglass/openapi/stormglass-marine-api-openapi.yml
- filename: stormglass-solar-api-openapi.yml
  format: yaml
  label: Stormglass Solar API
  slug: stormglass-solar-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stormglass/openapi/stormglass-solar-api-openapi.yml
- filename: stormglass-tides-api-openapi.yml
  format: yaml
  label: Stormglass Tides API
  slug: stormglass-tides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stormglass/openapi/stormglass-tides-api-openapi.yml
- filename: stormglass-weather-api-openapi.yml
  format: yaml
  label: Stormglass Weather API
  slug: stormglass-weather-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stormglass/openapi/stormglass-weather-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You hereby confirm that you are 16 years of age or older, of legal age to enter into contracts
    value: '16'
  restricted_uses:
  - summary: Unlawful use
    text: You are solely responsible for not using the Services for any purpose that is prohibited by these Terms and Conditions or deemed unlawful by local legislation were you operate.
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
name: Stormglass
provenance_date: '2026-11-10'
provider_name: Stormglass
provider_slug: stormglass
slug: stormglass-eligibility
source_date: '2026-11-10'
source_filename: stormglass-eligibility.yml
source_heading: Eligibility
source_page: https://stormglass.io/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stormglass\naid: stormglass\nurl: https://stormglass.io/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: You are solely responsible for not using the Services for any purpose that is prohibited by these Terms\n    and Conditions or deemed unlawful by local legislation were you operate.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You hereby confirm that you are 16 years of age or older, of legal age to enter into\
  \ contracts\n"
source_yaml_url: https://artifacts.apis.io/stormglass/eligibility/stormglass-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Stormglass's own page on 2026-11-10.
synthetic: false
tags:
- Astronomy
- Bio
- Climate
- Elevation
- Forecasting
- Marine
- Ocean
- Solar
- Tides
- Weather
- Wind
---
