---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The World Account is to be used for commercial purposes.
    type: business
  minimum_age:
    text: You must be at least 18 years old to open and use a World Account.
    value: '18'
  restricted_uses:
  - summary: No investment or speculative FX
    text: World First does not support foreign exchange transactions entered into for investment or speculative purposes
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
name: WorldFirst
provenance_date: '2026-11-10'
provider_name: WorldFirst
provider_slug: worldfirst
slug: worldfirst-eligibility
source_date: '2026-11-10'
source_filename: worldfirst-eligibility.yml
source_heading: Eligibility
source_page: https://www.worldfirst.com/uk/legal/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WorldFirst\naid: worldfirst\nurl: https://www.worldfirst.com/uk/legal/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The World Account is to be used for commercial purposes.\nrestricted_uses:\n- summary: No investment or speculative FX\n  text: World First does not support foreign exchange transactions entered into for investment or speculative purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least\
  \ 18 years old to open and use a World Account.\n"
source_yaml_url: https://artifacts.apis.io/worldfirst/eligibility/worldfirst-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from WorldFirst's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- United Kingdom
- Cross-Border
- Money Transfer
- Foreign Exchange
- Payouts
- Payment Gateway
- E-Commerce
- Multi-Currency
- Card Issuing
- Cross-Border Payments
---
