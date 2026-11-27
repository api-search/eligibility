---
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
  - summary: Inspecting only owned or authorised hosts
    text: Only inspect URLs and hostnames you own or are authorised to test.
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
name: httpstatus-com
provenance_date: '2026-11-09'
provider_name: httpstatus-com
provider_slug: httpstatus-com
slug: httpstatus-com-eligibility
source_date: '2026-11-09'
source_filename: httpstatus-com-eligibility.yml
source_heading: Eligibility
source_page: https://httpstatus.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: httpstatus-com\naid: httpstatus-com\nurl: https://httpstatus.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Inspecting only owned or authorised hosts\n  text: Only inspect URLs and hostnames you own or are authorised to test.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/httpstatus-com/eligibility/httpstatus-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from httpstatus-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- HTTP
- Status-Codes
- Developer Tools
- Open Source
---
