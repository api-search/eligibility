---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: When you create an account with us, you guarantee that you are above the age of 18
    value: '18'
  restricted_uses:
  - summary: Offensive usernames
    text: You may not use as a username any name that is offensive, vulgar or obscene.
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
name: Payform
provenance_date: '2026-11-10'
provider_name: Payform
provider_slug: payform
slug: payform-eligibility
source_date: '2026-11-10'
source_filename: payform-eligibility.yml
source_heading: Eligibility
source_page: https://payform.me/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Payform\naid: payform\nurl: https://payform.me/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Offensive usernames\n  text: You may not use as a username any name that is offensive, vulgar or obscene.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: When you create an account with us, you guarantee that you are above the age of 18\n"
source_yaml_url: https://artifacts.apis.io/payform/eligibility/payform-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Payform's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Payment Forms
- No-Code
- Recurring Billing
- Subscription
- Checkout
- Digital Content
- Software-as-a-Service
---
