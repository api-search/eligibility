---
api_specs:
- filename: channels-dvr-apps-openapi-generated.yml
  format: yaml
  label: Channels DVR apps API
  slug: apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channels-dvr/openapi/_ae-authored/channels-dvr-apps-openapi-generated.yml
- filename: channels-dvr-server-openapi-generated.yml
  format: yaml
  label: Channels DVR server API
  slug: server-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channels-dvr/openapi/_ae-authored/channels-dvr-server-openapi-generated.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: must be over the age of 18
    value: '18'
  restricted_uses:
  - summary: Life-critical or mission-critical systems
    text: You may not use the Platform on a computer that is used to operate nuclear facilities, life support, or other mission critical applications where life or property may be at stake
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We reserve the right to verify all user credentials and to reject any users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Channels DVR
provenance_date: '2026-11-09'
provider_name: Channels DVR
provider_slug: channels-dvr
slug: channels-dvr-eligibility
source_date: '2026-11-09'
source_filename: channels-dvr-eligibility.yml
source_heading: Eligibility
source_page: https://getchannels.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Channels DVR\naid: channels-dvr\nurl: https://getchannels.com/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Life-critical or mission-critical systems\n  text: You may not use the Platform on a computer that is used to operate nuclear facilities, life support, or\n    other mission critical applications where life or property may be at stake\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We reserve the right to verify all user credentials and to reject any users.\nminimum_age:\n  value: '18'\n\
  \  text: must be over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/channels-dvr/eligibility/channels-dvr-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Channels DVR's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Streaming
- DVR
- TV
- Automation
---
