---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are an individual, you must be either (a) at least 18 years old or (b) at least 13 years old and have been authorized by your parent or guardian to use the Boku Service.
    type: individual
  - text: If you represent a business, you must be duly authorized to enter into this Agreement on behalf of the business.
    type: business
  minimum_age:
    text: you must be either (a) at least 18 years old or (b) at least 13 years old and have been authorized by your parent or guardian to use the Boku Service.
    value: '13'
  restricted_uses:
  - summary: Illegal or fraudulent use
    text: The Boku Services may only be used for the purpose of the transacting with authorized Merchants and not for any illegal, fraudulent purposes of any kind.
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
name: Boku
provenance_date: '2026-11-09'
provider_name: Boku
provider_slug: boku
slug: boku-eligibility
source_date: '2026-11-09'
source_filename: boku-eligibility.yml
source_heading: Eligibility
source_page: https://www.boku.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boku\naid: boku\nurl: https://www.boku.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are an individual, you must be either (a) at least 18 years old or (b) at least 13 years old and\n    have been authorized by your parent or guardian to use the Boku Service.\n- type: business\n  text: If you represent a business, you must be duly authorized to enter into this Agreement on behalf of the business.\nrestricted_uses:\n- summary: Illegal or fraudulent use\n  text: The Boku Services may only be used for the\
  \ purpose of the transacting with authorized Merchants and not\n    for any illegal, fraudulent purposes of any kind.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you must be either (a) at least 18 years old or (b) at least 13 years old and have been authorized by your\n    parent or guardian to use the Boku Service.\n"
source_yaml_url: https://artifacts.apis.io/boku/eligibility/boku-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Boku's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Mobile Payments
- Carrier Billing
- Digital Wallet
- Local Payment Methods
- Subscription
- Fintech
---
