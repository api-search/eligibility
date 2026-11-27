---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A "User" is an individual that has registered with us to use our service.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Compliance with laws
    text: You agree to comply with all applicable domestic and international laws, statutes, ordinances, and regulations regarding your use of our Website.
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
name: Gift Up!
provenance_date: '2026-11-09'
provider_name: Gift Up!
provider_slug: gift-up
slug: gift-up-eligibility
source_date: '2026-11-09'
source_filename: gift-up-eligibility.yml
source_heading: Eligibility
source_page: https://www.giftup.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Gift Up!\naid: gift-up\nurl: https://www.giftup.com/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A \"User\" is an individual that has registered with us to use our service.\nrestricted_uses:\n- summary: Compliance with laws\n  text: You agree to comply with all applicable domestic and international laws, statutes, ordinances, and regulations\n    regarding your use of our Website.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/gift-up/eligibility/gift-up-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Gift Up!'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- E-Commerce
- Gift Cards
- Software-as-a-Service
---
