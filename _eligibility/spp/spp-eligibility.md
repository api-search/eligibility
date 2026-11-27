---
api_specs:
- filename: spp-forecasting-api-openapi.yml
  format: yaml
  label: Southwest Power Pool Forecasting API
  slug: spp-forecasting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spp/openapi/spp-forecasting-api-openapi.yml
- filename: spp-monitoring-sets-api-openapi.yml
  format: yaml
  label: Southwest Power Pool Monitoring Sets API
  slug: spp-monitoring-sets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spp/openapi/spp-monitoring-sets-api-openapi.yml
- filename: spp-seasonal-api-openapi.yml
  format: yaml
  label: Southwest Power Pool Seasonal API
  slug: spp-seasonal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spp/openapi/spp-seasonal-api-openapi.yml
- filename: spp-seasonal-overrides-api-openapi.yml
  format: yaml
  label: Southwest Power Pool Seasonal Overrides API
  slug: spp-seasonal-overrides-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spp/openapi/spp-seasonal-overrides-api-openapi.yml
- filename: spp-temporary-aar-exceptions-api-openapi.yml
  format: yaml
  label: Southwest Power Pool Temporary AAR Exceptions API
  slug: spp-temporary-aar-exceptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spp/openapi/spp-temporary-aar-exceptions-api-openapi.yml
- filename: spp-realtime-api-openapi.yml
  format: yaml
  label: Southwest Power Pool Realtime API
  slug: spp-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spp/openapi/spp-realtime-api-openapi.yml
claim_count: 1
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
  - summary: Commercial use
    text: Any commercial use of these materials requires prior, express written authorization from the author(s) or a duly authorized officer of SPP.
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
name: Southwest Power Pool
provenance_date: '2026-11-10'
provider_name: Southwest Power Pool
provider_slug: spp
slug: spp-eligibility
source_date: '2026-11-10'
source_filename: spp-eligibility.yml
source_heading: Eligibility
source_page: https://www.spp.org/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Southwest Power Pool\naid: spp\nurl: https://www.spp.org/terms-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial use\n  text: Any commercial use of these materials requires prior, express written authorization from the author(s) or\n    a duly authorized officer of SPP.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spp/eligibility/spp-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Southwest Power Pool's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United States
- Energy Markets
- Electricity
- Grid
- Utilities
- Renewables
- Market Data
- Transmission
- System Operator
---
