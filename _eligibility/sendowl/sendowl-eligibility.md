---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be 18 years or older to use Service, and old enough to enter into a binding agreement for the sale and purchase of goods and services in your country of residence
    type: individual
  - text: If you are representing a business entity, have the authority to enter into a binding agreement on behalf of the business
    type: business
  minimum_age:
    text: Be 18 years or older to use Service
    value: '18'
  restricted_uses:
  - summary: Referral promotion limits
    text: When using this scheme, you may not promote or advertise SendOwl on any coupon, deal or discount site, via any pay-per-click advertising or on any search engine or social media platform.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Enter a valid email address and legal name
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SendOwl
provenance_date: '2026-11-10'
provider_name: SendOwl
provider_slug: sendowl
slug: sendowl-eligibility
source_date: '2026-11-10'
source_filename: sendowl-eligibility.yml
source_heading: Eligibility
source_page: https://www.sendowl.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SendOwl\naid: sendowl\nurl: https://www.sendowl.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be 18 years or older to use Service, and old enough to enter into a binding agreement for the sale and purchase\n    of goods and services in your country of residence\n- type: business\n  text: If you are representing a business entity, have the authority to enter into a binding agreement on behalf\n    of the business\nrestricted_uses:\n- summary: Referral promotion limits\n  text: When using this scheme, you may not promote\
  \ or advertise SendOwl on any coupon, deal or discount site, via\n    any pay-per-click advertising or on any search engine or social media platform.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Enter a valid email address and legal name\nminimum_age:\n  value: '18'\n  text: Be 18 years or older to use Service\n"
source_yaml_url: https://artifacts.apis.io/sendowl/eligibility/sendowl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from SendOwl's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Digital Products
- Payments
- Subscription
- Checkout
- Membership
- Licensing
- Creator Economy
- Webhook
---
