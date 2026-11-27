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
  - summary: Pay-by-Link fraud or unlawful use
    text: You must not generate or distribute payment links in connection with fraudulent, misleading, or unlawful activity.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The account sign-up request must be approved by one of the company’s statutory directors or a VAT-registered sole trader.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Telleroo
provenance_date: '2026-11-10'
provider_name: Telleroo
provider_slug: telleroo
slug: telleroo-eligibility
source_date: '2026-11-10'
source_filename: telleroo-eligibility.yml
source_heading: Eligibility
source_page: https://www.telleroo.com/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Telleroo\naid: telleroo\nurl: https://www.telleroo.com/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Pay-by-Link fraud or unlawful use\n  text: You must not generate or distribute payment links in connection with fraudulent, misleading, or unlawful\n    activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The account sign-up request must be approved by one of the company’s statutory directors or a VAT-registered\n    sole trader.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/telleroo/eligibility/telleroo-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Telleroo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Bulk Payments
- Payroll
- Faster Payments
- E-Money
- Fintech
- Banking
- International Payments
- Embedded Finance
---
