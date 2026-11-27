---
api_specs:
- filename: strava-activities-api-openapi.yml
  format: yaml
  label: Strava Activities API
  slug: strava-activities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-activities-api-openapi.yml
- filename: strava-athletes-api-openapi.yml
  format: yaml
  label: Strava Athletes API
  slug: strava-athletes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-athletes-api-openapi.yml
- filename: strava-clubs-api-openapi.yml
  format: yaml
  label: Strava Clubs API
  slug: strava-clubs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-clubs-api-openapi.yml
- filename: strava-gear-api-openapi.yml
  format: yaml
  label: Strava Gear API
  slug: strava-gear-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-gear-api-openapi.yml
- filename: strava-routes-api-openapi.yml
  format: yaml
  label: Strava Routes API
  slug: strava-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-routes-api-openapi.yml
- filename: strava-segment-efforts-api-openapi.yml
  format: yaml
  label: Strava Segment Efforts API
  slug: strava-segment-efforts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-segment-efforts-api-openapi.yml
- filename: strava-segments-api-openapi.yml
  format: yaml
  label: Strava Segments API
  slug: strava-segments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-segments-api-openapi.yml
- filename: strava-streams-api-openapi.yml
  format: yaml
  label: Strava Streams API
  slug: strava-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/strava/openapi/strava-streams-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are part of an agency, department or other entity of the U.S. Government, the use, duplication, reproduction, release, modification, disclosure or transfer of the Strava API Materials are restricted in accordance with the Federal Acquisition Regulations
    type: government
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Respect user privacy choices
    text: This includes not sharing a Strava user’s data with other users, end users of your application, or third parties without explicit consent.
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
name: Strava
provenance_date: '2026-11-10'
provider_name: Strava
provider_slug: strava
slug: strava-eligibility
source_date: '2026-11-10'
source_filename: strava-eligibility.yml
source_heading: Eligibility
source_page: https://www.strava.com/legal/api
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Strava\naid: strava\nurl: https://www.strava.com/legal/api\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If you are part of an agency, department or other entity of the U.S. Government, the use, duplication, reproduction,\n    release, modification, disclosure or transfer of the Strava API Materials are restricted in accordance with\n    the Federal Acquisition Regulations\nrestricted_uses:\n- summary: Respect user privacy choices\n  text: This includes not sharing a Strava user’s data with other users, end users of your application,\
  \ or third\n    parties without explicit consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/strava/eligibility/strava-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Strava's own page on 2026-11-10.
synthetic: false
tags:
- Cycling
- Fitness
- Fitness Tracking
- Running
- Sports
---
