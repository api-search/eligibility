---
api_specs:
- filename: air-quality-programmatic-apis-air-quality-programmatic-apis-real-time-air-quality-tile-api-api-openapi.yml
  format: yaml
  label: Air Quality Programmatic APIs Air Quality Programmatic APIs Real Time Air Quality Tile API
  slug: air-quality-programmatic-apis-air-quality-programmatic-apis-real-time-air-quality-tile-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/air-quality-programmatic-apis/openapi/air-quality-programmatic-apis-air-quality-programmatic-apis-real-time-air-quality-tile-api-api-openapi.yml
- filename: air-quality-programmatic-apis-stations-api-openapi.yml
  format: yaml
  label: Air Quality Programmatic APIs Stations API
  slug: air-quality-programmatic-apis-stations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/air-quality-programmatic-apis/openapi/air-quality-programmatic-apis-stations-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Public usage by for-profit corporations requires explicit agreement wit the World Air Quality Index team.
    type: business
  - text: Public usage by non-profit organization requires prior notification (by email) to the World Air Quality Index team.
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sale or paid applications
    text: The data can not be used in paid applications or services.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: A valid key must be used for accessing the API.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Air Quality Programmatic APIs
provenance_date: '2026-11-09'
provider_name: Air Quality Programmatic APIs
provider_slug: air-quality-programmatic-apis
slug: air-quality-programmatic-apis-eligibility
source_date: '2026-11-09'
source_filename: air-quality-programmatic-apis-eligibility.yml
source_heading: Eligibility
source_page: https://aqicn.org/api/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Air Quality Programmatic APIs\naid: air-quality-programmatic-apis\nurl: https://aqicn.org/api/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Public usage by for-profit corporations requires explicit agreement wit the World Air Quality Index team.\n- type: nonprofit\n  text: Public usage by non-profit organization requires prior notification (by email) to the World Air Quality\n    Index team.\nrestricted_uses:\n- summary: No sale or paid applications\n  text: The data can not be used in paid applications or services.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: A valid key must be used for accessing the API.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/air-quality-programmatic-apis/eligibility/air-quality-programmatic-apis-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Air Quality Programmatic APIs's own page on 2026-11-09.
synthetic: false
tags:
- Air Quality
- Environment
- EPA
- Open Data
- Public Health
- IoT
- Government Data
- Real-Time Data
---
