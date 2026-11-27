---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using the Platform, you affirm that you are at least 18 years of age
    type: individual
  minimum_age:
    text: you affirm that you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Commercial use of content prohibited
    text: for your personal and non-commercial purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must register an account on the Platform through a mobile number-based OTP verification system.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rigi
provenance_date: '2026-11-10'
provider_name: Rigi
provider_slug: rigi
slug: rigi-eligibility
source_date: '2026-11-10'
source_filename: rigi-eligibility.yml
source_heading: Eligibility
source_page: https://rigi.club/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rigi\naid: rigi\nurl: https://rigi.club/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using the Platform, you affirm that you are at least 18 years of age\nrestricted_uses:\n- summary: Commercial use of content prohibited\n  text: for your personal and non-commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must register an account on the Platform through a mobile number-based OTP verification system.\nminimum_age:\n  value: '18'\n  text: you affirm that you are\
  \ at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/rigi/eligibility/rigi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Rigi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Media
- Entertainment
- Streaming
- Video
- Short-Form Video
- OTT
- Mobile App
- India
---
