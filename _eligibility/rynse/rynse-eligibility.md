---
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
  - summary: Political campaigns or lobbying
    text: use the Services or Software in connection with any political campaigns or lobbying activities
  - summary: Embargoed countries and designated persons
    text: the Controlled Subject Matter will not be used or transferred or otherwise exported or re-exported to countries as to which the United States maintains an embargo
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
name: Rynse
provenance_date: '2026-11-10'
provider_name: Rynse
provider_slug: rynse
slug: rynse-eligibility
source_date: '2026-11-10'
source_filename: rynse-eligibility.yml
source_heading: Eligibility
source_page: https://www.gorynse.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rynse\naid: rynse\nurl: https://www.gorynse.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Political campaigns or lobbying\n  text: use the Services or Software in connection with any political campaigns or lobbying activities\n- summary: Embargoed countries and designated persons\n  text: the Controlled Subject Matter will not be used or transferred or otherwise exported or re-exported to countries\n    as to which the United States maintains an embargo\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rynse/eligibility/rynse-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Rynse's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fleet Management
- Washing
- Vehicle Care
- Software-as-a-Service
---
