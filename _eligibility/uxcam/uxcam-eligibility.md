---
api_specs:
- filename: uxcam-events-api-openapi.yml
  format: yaml
  label: UXCam Events API
  slug: uxcam-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uxcam/openapi/uxcam-events-api-openapi.yml
- filename: uxcam-sessions-api-openapi.yml
  format: yaml
  label: UXCam Sessions API
  slug: uxcam-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uxcam/openapi/uxcam-sessions-api-openapi.yml
- filename: uxcam-users-api-openapi.yml
  format: yaml
  label: UXCam Users API
  slug: uxcam-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uxcam/openapi/uxcam-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are accessing or using the service on behalf of a company or other legal entity, You represent and warrant that You are an authorized representative of that entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No personal data collection
    text: UXCam prohibits You from using the Services to collect, track or record any Personal Data.
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
name: UXCam
provenance_date: '2026-11-10'
provider_name: UXCam
provider_slug: uxcam
slug: uxcam-eligibility
source_date: '2026-11-10'
source_filename: uxcam-eligibility.yml
source_heading: Eligibility
source_page: https://help.uxcam.com/en/articles/10222767-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: UXCam\naid: uxcam\nurl: https://help.uxcam.com/en/articles/10222767-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are accessing or using the service on behalf of a company or other legal entity, You represent and\n    warrant that You are an authorized representative of that entity\nrestricted_uses:\n- summary: No personal data collection\n  text: UXCam prohibits You from using the Services to collect, track or record any Personal Data.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/uxcam/eligibility/uxcam-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from UXCam's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Product Analytics
- Session Replay
- Mobile Analytics
- Heatmaps
- User Experience
- Crash Reporting
---
