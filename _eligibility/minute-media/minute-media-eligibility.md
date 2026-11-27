---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You may not register or use the Service if you are under 18 years of age, the age of majority in the jurisdiction you are located in
    value: '18'
  restricted_uses:
  - summary: Age minimum for use
    text: You may not register or use the Service if you are under 18 years of age
  - summary: Betting content age limit
    text: all betting content on the Website is intended for individuals 21 or older or the applicable legal gambling age in the jurisdiction you are located in
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: we may also require you to provide proof of identification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Minute Media
provenance_date: '2026-11-10'
provider_name: Minute Media
provider_slug: minute-media
slug: minute-media-eligibility
source_date: '2026-11-10'
source_filename: minute-media-eligibility.yml
source_heading: Eligibility
source_page: https://www.minutegroup.com/policies/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Minute Media\naid: minute-media\nurl: https://www.minutegroup.com/policies/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Age minimum for use\n  text: You may not register or use the Service if you are under 18 years of age\n- summary: Betting content age limit\n  text: all betting content on the Website is intended for individuals 21 or older or the applicable legal gambling\n    age in the jurisdiction you are located in\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: we may\
  \ also require you to provide proof of identification\nminimum_age:\n  value: '18'\n  text: You may not register or use the Service if you are under 18 years of age, the age of majority in the jurisdiction\n    you are located in\n"
source_yaml_url: https://artifacts.apis.io/minute-media/eligibility/minute-media-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Minute Media's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- Sports
- Advertising
- Video
- Publishing
- AdTech
- Content
- oEmbed
- Online Video Platform
---
