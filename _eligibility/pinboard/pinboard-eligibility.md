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
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: The only signup requirements are payment and a working email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pinboard
provenance_date: '2026-11-10'
provider_name: Pinboard
provider_slug: pinboard
slug: pinboard-eligibility
source_date: '2026-11-10'
source_filename: pinboard-eligibility.yml
source_heading: Eligibility
source_page: https://pinboard.in/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pinboard\naid: pinboard\nurl: https://pinboard.in/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: The only signup requirements are payment and a working email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pinboard/eligibility/pinboard-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Pinboard's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Bookmarking
- Social
- Productivity
- Web
---
