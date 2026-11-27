---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Clause 11.1 refers to residents of 'certain countries where we do not or cannot do business' without naming them.
  entity_types:
  - text: Personal accounts are intended only to be used for Transactions related to personal, family or household purposes.
    type: individual
  - text: Business accounts should be used when you are conducting Transactions for commercial purposes such as the sale of goods and services.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Personal accounts limited to personal use
    text: Personal accounts may not be used for business, commercial or merchant transactions.
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
name: OFX (OzForex)
provenance_date: '2026-11-10'
provider_name: OFX (OzForex)
provider_slug: ozforex
slug: ozforex-eligibility
source_date: '2026-11-10'
source_filename: ozforex-eligibility.yml
source_heading: Eligibility
source_page: https://www.ofx.com/en-us/legal/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OFX (OzForex)\naid: ozforex\nurl: https://www.ofx.com/en-us/legal/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Clause 11.1 refers to residents of 'certain countries where we do not or cannot do business' without naming\n    them.\nentity_types:\n- type: individual\n  text: Personal accounts are intended only to be used for Transactions related to personal, family or household\n    purposes.\n- type: business\n  text: Business accounts should be used when you are conducting Transactions for commercial purposes such as the\n    sale of goods\
  \ and services.\nrestricted_uses:\n- summary: Personal accounts limited to personal use\n  text: Personal accounts may not be used for business, commercial or merchant transactions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ozforex/eligibility/ozforex-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from OFX (OzForex)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Money Transfer
- Foreign Exchange
- International Payments
- Payments
- Currency
- Fintech
---
