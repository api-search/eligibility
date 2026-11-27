---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: This Site is not offered to any person under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Illegal activity content
    text: advocates or provides instructions or ideas relating to any illegal activity or any intent to commit any illegal activity.
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
name: Frame Payments
provenance_date: '2026-11-09'
provider_name: Frame Payments
provider_slug: frame-payments
slug: frame-payments-eligibility
source_date: '2026-11-09'
source_filename: frame-payments-eligibility.yml
source_heading: Eligibility
source_page: https://framepayments.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Frame Payments\naid: frame-payments\nurl: https://framepayments.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal activity content\n  text: advocates or provides instructions or ideas relating to any illegal activity or any intent to commit any\n    illegal activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: This Site is not offered to any person under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/frame-payments/eligibility/frame-payments-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Frame Payments's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Financial Services
- Fintech
- KYC
- Compliance
- Fraud Prevention
- Billing
- Payouts
- Identity Verification
---
