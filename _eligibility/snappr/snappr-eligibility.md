---
api_specs:
- filename: snappr-availability-api-openapi.yml
  format: yaml
  label: Snappr Availability API
  slug: snappr-availability-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappr/openapi/snappr-availability-api-openapi.yml
- filename: snappr-bookings-api-openapi.yml
  format: yaml
  label: Snappr Bookings API
  slug: snappr-bookings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappr/openapi/snappr-bookings-api-openapi.yml
- filename: snappr-coverage-api-openapi.yml
  format: yaml
  label: Snappr Coverage API
  slug: snappr-coverage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappr/openapi/snappr-coverage-api-openapi.yml
- filename: snappr-editing-job-types-api-openapi.yml
  format: yaml
  label: Snappr Editing Job Types API
  slug: snappr-editing-job-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappr/openapi/snappr-editing-job-types-api-openapi.yml
- filename: snappr-editing-jobs-api-openapi.yml
  format: yaml
  label: Snappr Editing Jobs API
  slug: snappr-editing-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappr/openapi/snappr-editing-jobs-api-openapi.yml
- filename: snappr-images-api-openapi.yml
  format: yaml
  label: Snappr Images API
  slug: snappr-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappr/openapi/snappr-images-api-openapi.yml
- filename: snappr-presets-api-openapi.yml
  format: yaml
  label: Snappr Presets API
  slug: snappr-presets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappr/openapi/snappr-presets-api-openapi.yml
- filename: snappr-shoot-types-api-openapi.yml
  format: yaml
  label: Snappr Shoot Types API
  slug: snappr-shoot-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappr/openapi/snappr-shoot-types-api-openapi.yml
- filename: snappr-videos-api-openapi.yml
  format: yaml
  label: Snappr Videos API
  slug: snappr-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/snappr/openapi/snappr-videos-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 years old, you may use the Service, with or without registering, only with the approval of your parent or guardian.
    type: individual
  - text: “ User ” “ you ” or “ your ” means a person, organization or entity using the Services, including Subjects and Photographers.
    type: business
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Export controls
    text: No Software may be downloaded from the Service or otherwise exported or re-exported in violation of U.S. export laws.
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
name: Snappr
provenance_date: '2026-11-10'
provider_name: Snappr
provider_slug: snappr
slug: snappr-eligibility
source_date: '2026-11-10'
source_filename: snappr-eligibility.yml
source_heading: Eligibility
source_page: https://www.snappr.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Snappr\naid: snappr\nurl: https://www.snappr.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 years old, you may use the Service, with or without registering, only with the approval\n    of your parent or guardian.\n- type: business\n  text: “ User ” “ you ” or “ your ” means a person, organization or entity using the Services, including Subjects\n    and Photographers.\nrestricted_uses:\n- summary: Export controls\n  text: No Software may be downloaded from the Service or otherwise exported\
  \ or re-exported in violation of U.S.\n    export laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/snappr/eligibility/snappr-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Snappr's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Photography
- Videography
- Visual Content
- Photo Editing
- On-Demand
- Enterprise
---
