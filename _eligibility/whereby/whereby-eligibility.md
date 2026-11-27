---
api_specs:
- filename: whereby-insights-api-openapi.yml
  format: yaml
  label: Whereby Insights API
  slug: whereby-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whereby/openapi/whereby-insights-api-openapi.yml
- filename: whereby-meetings-api-openapi.yml
  format: yaml
  label: Whereby Meetings API
  slug: whereby-meetings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whereby/openapi/whereby-meetings-api-openapi.yml
- filename: whereby-recordings-api-openapi.yml
  format: yaml
  label: Whereby Recordings API
  slug: whereby-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whereby/openapi/whereby-recordings-api-openapi.yml
- filename: whereby-rooms-api-openapi.yml
  format: yaml
  label: Whereby Rooms API
  slug: whereby-rooms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whereby/openapi/whereby-rooms-api-openapi.yml
- filename: whereby-summaries-api-openapi.yml
  format: yaml
  label: Whereby Summaries API
  slug: whereby-summaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whereby/openapi/whereby-summaries-api-openapi.yml
- filename: whereby-transcriptions-api-openapi.yml
  format: yaml
  label: Whereby Transcriptions API
  slug: whereby-transcriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/whereby/openapi/whereby-transcriptions-api-openapi.yml
claim_count: 2
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
  - summary: Export control
    text: You shall not export or re-export the Service or parts of it in violation of such laws or regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must use a valid email address, and Whereby reserves the right to verify this at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Whereby
provenance_date: '2026-11-10'
provider_name: Whereby
provider_slug: whereby
slug: whereby-eligibility
source_date: '2026-11-10'
source_filename: whereby-eligibility.yml
source_heading: Eligibility
source_page: https://whereby.com/information/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Whereby\naid: whereby\nurl: https://whereby.com/information/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export control\n  text: You shall not export or re-export the Service or parts of it in violation of such laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must use a valid email address, and Whereby reserves the right to verify this at any time.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/whereby/eligibility/whereby-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Whereby's own page on 2026-11-10.
synthetic: false
tags:
- Video
- Communications
- Real-Time
- WebRTC
- Embedded
- Meetings
- Collaboration
---
