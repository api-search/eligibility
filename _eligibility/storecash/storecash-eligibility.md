---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Our Services are intended solely for users who are 13 years of age or older.
    type: individual
  minimum_age:
    text: Our Services are intended solely for users who are 13 years of age or older.
    value: '13'
  restricted_uses:
  - summary: Illegal or unauthorized purposes
    text: Use the Services for any illegal or unauthorized purpose or engage in, encourage, or promote any illegal activity
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
name: StoreCash
provenance_date: '2026-11-10'
provider_name: StoreCash
provider_slug: storecash
slug: storecash-eligibility
source_date: '2026-11-10'
source_filename: storecash-eligibility.yml
source_heading: Eligibility
source_page: https://www.storecashapp.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StoreCash\naid: storecash\nurl: https://www.storecashapp.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Our Services are intended solely for users who are 13 years of age or older.\nrestricted_uses:\n- summary: Illegal or unauthorized purposes\n  text: Use the Services for any illegal or unauthorized purpose or engage in, encourage, or promote any illegal\n    activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our Services are intended\
  \ solely for users who are 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/storecash/eligibility/storecash-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from StoreCash's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cashback
- Rewards
- Payments
- Fintech
- Loyalty
- Consumer Finance
- Mobile App
---
