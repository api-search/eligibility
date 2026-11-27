---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer is a business and not an individual consumer
    type: business
  minimum_age:
    text: Our services are not intended for children under 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Personal, family or household purpose
    text: any personal, family, or household purpose
  - summary: Gambling
    text: any gambling transaction or gambling activity
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
name: Mesh Payments
provenance_date: '2026-11-10'
provider_name: Mesh Payments
provider_slug: mesh-payments
slug: mesh-payments-eligibility
source_date: '2026-11-10'
source_filename: mesh-payments-eligibility.yml
source_heading: Eligibility
source_page: https://meshpayments.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mesh Payments\naid: mesh-payments\nurl: https://meshpayments.com/legal/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer is a business and not an individual consumer\nrestricted_uses:\n- summary: Personal, family or household purpose\n  text: any personal, family, or household purpose\n- summary: Gambling\n  text: any gambling transaction or gambling activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our services are not intended\
  \ for children under 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/mesh-payments/eligibility/mesh-payments-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mesh Payments's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Spend Management
- Expense Management
- Corporate Cards
- Travel
- Accounts Payable
- Fintech
- Card Issuing
- Accounting Automation
---
