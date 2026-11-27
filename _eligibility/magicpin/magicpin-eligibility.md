---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: If you are under the age of majority as per the laws of your country of residence ( “Minimum Age” ) you may not register for an account.
    value: age of majority
  restricted_uses:
  - summary: No illegal use
    text: You must not use the service for any illegal purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: verify your identity to permit you to undertake transactions
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Magicpin
provenance_date: '2026-11-10'
provider_name: Magicpin
provider_slug: magicpin
slug: magicpin-eligibility
source_date: '2026-11-10'
source_filename: magicpin-eligibility.yml
source_heading: Eligibility
source_page: https://magicpin.in/partner/store/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Magicpin\naid: magicpin\nurl: https://magicpin.in/partner/store/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No illegal use\n  text: You must not use the service for any illegal purpose.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: verify your identity to permit you to undertake transactions\nminimum_age:\n  value: age of majority\n  text: If you are under the age of majority as per the laws of your country of residence ( “Minimum Age” ) you\n    may not register for\
  \ an account.\n"
source_yaml_url: https://artifacts.apis.io/magicpin/eligibility/magicpin-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Magicpin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Savings
- Discounts
- Hyperlocal
- Food Delivery
- Retail
- Cashback
- Vouchers
- India
---
