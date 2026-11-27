---
api_specs:
- filename: wideo-automation-api-openapi.yml
  format: yaml
  label: Wideo Automation API
  slug: wideo-automation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wideo/openapi/wideo-automation-api-openapi.yml
- filename: wideo-batch-api-openapi.yml
  format: yaml
  label: Wideo Batch API
  slug: wideo-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wideo/openapi/wideo-batch-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: By using the Services you represent that you are 13 years of age or older
    value: '13'
  restricted_uses:
  - summary: Users under 13
    text: Wideo will never knowingly solicit, nor will it accept, personally identifiable information from users known to be under thirteen (13) years of age.
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
name: Wideo
provenance_date: '2026-11-10'
provider_name: Wideo
provider_slug: wideo
slug: wideo-eligibility
source_date: '2026-11-10'
source_filename: wideo-eligibility.yml
source_heading: Eligibility
source_page: https://wideo.co/terms-and-conditions-wideo/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wideo\naid: wideo\nurl: https://wideo.co/terms-and-conditions-wideo/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Users under 13\n  text: Wideo will never knowingly solicit, nor will it accept, personally identifiable information from users known\n    to be under thirteen (13) years of age.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: By using the Services you represent that you are 13 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/wideo/eligibility/wideo-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Wideo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Video Automation
- Content Creation
- Media
- Marketing
- Templates
- No-Code
---
