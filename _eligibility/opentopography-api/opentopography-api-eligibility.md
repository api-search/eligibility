---
api_specs:
- filename: opentopography-api-public-api-openapi.yml
  format: yaml
  label: OpenTopography API Public API
  slug: opentopography-api-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/opentopography-api/openapi/opentopography-api-public-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 16 years old to create an account on OpenTopography.
    value: '16'
  restricted_uses:
  - summary: Life-critical functions
    text: OpenTopography data should not be used for any life-critical functions.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: We do not require account holders to provide a form of government identification or other information or undertake additional checks designed to help verify the identities.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: OpenTopography API
provenance_date: '2026-11-10'
provider_name: OpenTopography API
provider_slug: opentopography-api
slug: opentopography-api-eligibility
source_date: '2026-11-10'
source_filename: opentopography-api-eligibility.yml
source_heading: Eligibility
source_page: https://opentopography.org/usageterms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OpenTopography API\naid: opentopography-api\nurl: https://opentopography.org/usageterms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Life-critical functions\n  text: OpenTopography data should not be used for any life-critical functions.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: We do not require account holders to provide a form of government identification or other information or\n    undertake additional checks designed to help verify the identities.\nminimum_age:\n  value: '16'\n  text:\
  \ You must be at least 16 years old to create an account on OpenTopography.\n"
source_yaml_url: https://artifacts.apis.io/opentopography-api/eligibility/opentopography-api-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from OpenTopography API's own page on 2026-11-10.
synthetic: false
tags:
- DEM
- Data
- Elevation
- Geospatial
- LiDAR
- Topographical
- Topography
---
