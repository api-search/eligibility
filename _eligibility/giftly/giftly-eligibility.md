---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are a U.S. citizen or legal alien residing in the United States
  entity_types:
  - text: you are at least eighteen (18) years of age
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Illegitimate or violating redemptions
    text: Giftly and FIBT reserve the right to deny any redemption requests deemed to be illegitimate or in violation of these terms of service.
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
name: Giftly
provenance_date: '2026-11-09'
provider_name: Giftly
provider_slug: giftly
slug: giftly-eligibility
source_date: '2026-11-09'
source_filename: giftly-eligibility.yml
source_heading: Eligibility
source_page: https://www.giftly.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Giftly\naid: giftly\nurl: https://www.giftly.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are a U.S. citizen or legal alien residing in the United States\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years of age\nrestricted_uses:\n- summary: Illegitimate or violating redemptions\n  text: Giftly and FIBT reserve the right to deny any redemption requests deemed to be illegitimate or in violation\n    of these terms of service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/giftly/eligibility/giftly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Giftly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gift Cards
- Gifting
- Payments
- Prepaid
- Consumer
- E-Commerce
- Rewards
---
