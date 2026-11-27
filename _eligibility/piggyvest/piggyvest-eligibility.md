---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - NG
    text: Currently, this Website operates only in Nigeria, and is only available to users who have Nigerian bank accounts.
  minimum_age:
    text: be a Nigerian citizen (or a legal Nigerian resident) of at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Personal use only
    text: You may only use the Services for your own personal, non-commercial use and not on behalf of or for the benefit of any third party.
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
name: PiggyVest
provenance_date: '2026-11-10'
provider_name: PiggyVest
provider_slug: piggyvest
slug: piggyvest-eligibility
source_date: '2026-11-10'
source_filename: piggyvest-eligibility.yml
source_heading: Eligibility
source_page: https://www.piggyvest.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PiggyVest\naid: piggyvest\nurl: https://www.piggyvest.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - NG\n  excluded: []\n  text: Currently, this Website operates only in Nigeria, and is only available to users who have Nigerian bank\n    accounts.\nentity_types: []\nrestricted_uses:\n- summary: Personal use only\n  text: You may only use the Services for your own personal, non-commercial use and not on behalf of or for the\n    benefit of any third party.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be a Nigerian citizen\
  \ (or a legal Nigerian resident) of at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/piggyvest/eligibility/piggyvest-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from PiggyVest's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Savings
- Investment
- Digital Wallet
- Micro Savings
- Goal Based Savings
- Fixed Deposit
- Dollar Savings
- Consumer Finance
- Personal Finance
- Mobile Banking
- Business Banking
- Wallet API
- Transfers
- Bank Transfers
- Scheduled Payments
- Webhook
- Hosted Checkout
- Pay With Pocket
- Invoicing
- Reserved Accounts
- Africa
- Nigeria
- Lagos
---
