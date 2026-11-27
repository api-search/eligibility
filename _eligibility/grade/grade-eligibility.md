---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful campaigns
    text: use Grade for unlawful campaigns or activities.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Grade's financial workflows comply with international KYC/AML regulations, and identity verification may be required before funds are released.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Grade
provenance_date: '2026-11-09'
provider_name: Grade
provider_slug: grade
slug: grade-eligibility
source_date: '2026-11-09'
source_filename: grade-eligibility.yml
source_heading: Eligibility
source_page: https://usegrade.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Grade\naid: grade\nurl: https://usegrade.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful campaigns\n  text: use Grade for unlawful campaigns or activities.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Grade's financial workflows comply with international KYC/AML regulations, and identity verification may\n    be required before funds are released.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/grade/eligibility/grade-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Grade's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payroll
- Payments
- Payouts
- Compliance
- Creator Economy
- Fintech
- Contractors
- Merchant of Record
---
