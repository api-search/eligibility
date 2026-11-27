---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent and warrant to BoxCast that you are of legal age to form a binding contract with BoxCast
    value: legal age
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
name: BoxCast
provenance_date: '2026-11-09'
provider_name: BoxCast
provider_slug: boxcast
slug: boxcast-eligibility
source_date: '2026-11-09'
source_filename: boxcast-eligibility.yml
source_heading: Eligibility
source_page: https://www.boxcast.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BoxCast\naid: boxcast\nurl: https://www.boxcast.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: You represent and warrant to BoxCast that you are of legal age to form a binding contract with BoxCast\n"
source_yaml_url: https://artifacts.apis.io/boxcast/eligibility/boxcast-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from BoxCast's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Streaming
- Live
- Platform
---
