---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: If you are a user having your usual residence in the United States, the Terms of Service here ( https://sweatco.in/tnc-us ) shall apply.
  entity_types:
  - text: The Licences are for your personal and domestic use only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial, business or resale use
    text: You must not use the Service for commercial, business or resale purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You should ensure that you use your personal mobile number for verification of your account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sweatcoin
provenance_date: '2026-11-10'
provider_name: Sweatcoin
provider_slug: sweatcoin
slug: sweatcoin-eligibility
source_date: '2026-11-10'
source_filename: sweatcoin-eligibility.yml
source_heading: Eligibility
source_page: https://sweatco.in/tnc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sweatcoin\naid: sweatcoin\nurl: https://sweatco.in/tnc\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: If you are a user having your usual residence in the United States, the Terms of Service here ( https://sweatco.in/tnc-us\n    ) shall apply.\nentity_types:\n- type: individual\n  text: The Licences are for your personal and domestic use only.\nrestricted_uses:\n- summary: Commercial, business or resale use\n  text: You must not use the Service for commercial, business or resale purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You should ensure\
  \ that you use your personal mobile number for verification of your account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sweatcoin/eligibility/sweatcoin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Sweatcoin's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fitness
- Health
- Wellness
- Movement
- Rewards
- Cryptocurrency
- Web3
- Consumer App
- Loyalty
---
