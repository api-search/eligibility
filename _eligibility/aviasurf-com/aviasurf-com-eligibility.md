---
api_specs:
- filename: aviasurf-com-health-api-openapi.yml
  format: yaml
  label: Aviasurf Health API
  slug: aviasurf-com-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviasurf-com/openapi/aviasurf-com-health-api-openapi.yml
- filename: aviasurf-com-prices-api-openapi.yml
  format: yaml
  label: Aviasurf Prices API
  slug: aviasurf-com-prices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviasurf-com/openapi/aviasurf-com-prices-api-openapi.yml
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
  - summary: Fraudulent or unlawful use
    text: use Aviasurf for fraudulent or unlawful purposes;
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
name: Aviasurf
provenance_date: '2026-11-09'
provider_name: Aviasurf
provider_slug: aviasurf-com
slug: aviasurf-com-eligibility
source_date: '2026-11-09'
source_filename: aviasurf-com-eligibility.yml
source_heading: Eligibility
source_page: https://aviasurf.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aviasurf\naid: aviasurf-com\nurl: https://aviasurf.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Fraudulent or unlawful use\n  text: use Aviasurf for fraudulent or unlawful purposes;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aviasurf-com/eligibility/aviasurf-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Aviasurf's own page on 2026-11-09.
synthetic: false
tags:
- Flights
- Travel
- Metasearch
- Booking
- Airlines
---
