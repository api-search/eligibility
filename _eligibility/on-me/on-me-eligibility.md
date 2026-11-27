---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The individual who engages with On Me's products or services.
    type: individual
  minimum_age:
    text: verifying that you meet the minimum age requirements of On Me and our card network partners (including Mastercard's requirement that cardholders be at least 13 years old)
    value: '13'
  restricted_uses:
  - summary: Gift cards cannot be used to buy stored value
    text: Gift Card Value or Gift Cards may not be used to purchase additional Gift Card Value, other Gift Cards, or any other stored-value instruments.
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
name: On Me
provenance_date: '2026-11-10'
provider_name: On Me
provider_slug: on-me
slug: on-me-eligibility
source_date: '2026-11-10'
source_filename: on-me-eligibility.yml
source_heading: Eligibility
source_page: https://onme.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: On Me\naid: on-me\nurl: https://onme.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The individual who engages with On Me's products or services.\nrestricted_uses:\n- summary: Gift cards cannot be used to buy stored value\n  text: Gift Card Value or Gift Cards may not be used to purchase additional Gift Card Value, other Gift Cards,\n    or any other stored-value instruments.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: verifying that you\
  \ meet the minimum age requirements of On Me and our card network partners (including Mastercard's\n    requirement that cardholders be at least 13 years old)\n"
source_yaml_url: https://artifacts.apis.io/on-me/eligibility/on-me-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from On Me's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gift Cards
- Digital Gifting
- Corporate Gifting
- Rewards and Incentives
- Payments
- Mobile Wallet
- Employee Recognition
- Consumer
---
