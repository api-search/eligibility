---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are over the age of 18 and have the right and authority to enter into these terms of use
    type: individual
  minimum_age:
    text: you are over the age of 18
    value: '18'
  restricted_uses:
  - summary: Unsolicited email advertising
    text: sending unsolicited email advertisements to any user of this website or this website is expressly prohibited by these Terms of Use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may undertake additional checks and processes designed to help verify or check the identities or backgrounds of Campsite Owners and/or Campsite Renters
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dyrt
provenance_date: '2026-11-09'
provider_name: Dyrt
provider_slug: dyrt
slug: dyrt-eligibility
source_date: '2026-11-09'
source_filename: dyrt-eligibility.yml
source_heading: Eligibility
source_page: https://thedyrt.com/about/tacos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dyrt\naid: dyrt\nurl: https://thedyrt.com/about/tacos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are over the age of 18 and have the right and authority to enter into these terms of use\nrestricted_uses:\n- summary: Unsolicited email advertising\n  text: sending unsolicited email advertisements to any user of this website or this website is expressly prohibited\n    by these Terms of Use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may undertake additional checks and processes\
  \ designed to help verify or check the identities or backgrounds\n    of Campsite Owners and/or Campsite Renters\nminimum_age:\n  value: '18'\n  text: you are over the age of 18\n"
source_yaml_url: https://artifacts.apis.io/dyrt/eligibility/dyrt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Dyrt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Camping
- Campgrounds
- RV
- Travel
- Outdoor Recreation
- Reviews
- Booking
- Consumer App
---
