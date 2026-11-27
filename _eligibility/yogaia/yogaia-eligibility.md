---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Service is intended for people who are at the age of majority (usually 18 years old or older).
    type: individual
  minimum_age:
    text: The Service is intended for people who are at the age of majority (usually 18 years old or older).
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: The Service is licensed to you for your personal and non-commercial use only.
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
name: Yogaia
provenance_date: '2026-11-10'
provider_name: Yogaia
provider_slug: yogaia
slug: yogaia-eligibility
source_date: '2026-11-10'
source_filename: yogaia-eligibility.yml
source_heading: Eligibility
source_page: https://yogaia.com/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Yogaia\naid: yogaia\nurl: https://yogaia.com/policies/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Service is intended for people who are at the age of majority (usually 18 years old or older).\nrestricted_uses:\n- summary: Non-commercial use only\n  text: The Service is licensed to you for your personal and non-commercial use only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is intended for people who are at the age of majority (usually\
  \ 18 years old or older).\n"
source_yaml_url: https://artifacts.apis.io/yogaia/eligibility/yogaia-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Yogaia's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Yoga
- Fitness
- Wellness
- Online Classes
- Subscription
- Consumer
- Streaming Video
---
