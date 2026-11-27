---
api_specs:
- filename: sunrise-sunset-json-api-openapi.yml
  format: yaml
  label: Sunrise Sunset Json API
  slug: sunrise-sunset-json-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sunrise-sunset/openapi/sunrise-sunset-json-api-openapi.yml
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
  - summary: Personal use only
    text: This site is for personal use only.
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
name: Sunrise Sunset
provenance_date: '2026-11-10'
provider_name: Sunrise Sunset
provider_slug: sunrise-sunset
slug: sunrise-sunset-eligibility
source_date: '2026-11-10'
source_filename: sunrise-sunset-eligibility.yml
source_heading: Eligibility
source_page: https://sunrise-sunset.org/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sunrise Sunset\naid: sunrise-sunset\nurl: https://sunrise-sunset.org/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Personal use only\n  text: This site is for personal use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sunrise-sunset/eligibility/sunrise-sunset-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Sunrise Sunset's own page on 2026-11-10.
synthetic: false
tags:
- Sunrise
- Sunset
- Solar
- Astronomy
- Twilight
- Weather
- Geolocation
- Free
---
