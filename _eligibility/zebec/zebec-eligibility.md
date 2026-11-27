---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Not all Services are available in all jurisdictions. Availability depends on: Regulatory permissions Licensing status Third-party partner availability Operational constraints'
  entity_types:
  - text: You are at least eighteen (18) years old or the age of majority in your jurisdiction
    type: individual
  minimum_age:
    text: You are at least eighteen (18) years old or the age of majority in your jurisdiction
    value: '18'
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
name: Zebec
provenance_date: '2026-11-10'
provider_name: Zebec
provider_slug: zebec
slug: zebec-eligibility
source_date: '2026-11-10'
source_filename: zebec-eligibility.yml
source_heading: Eligibility
source_page: https://zebec.io/superapp-terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zebec\naid: zebec\nurl: https://zebec.io/superapp-terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Not all Services are available in all jurisdictions. Availability depends on: Regulatory permissions Licensing\n    status Third-party partner availability Operational constraints'\nentity_types:\n- type: individual\n  text: You are at least eighteen (18) years old or the age of majority in your jurisdiction\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least eighteen\
  \ (18) years old or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/zebec/eligibility/zebec-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Zebec's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Payroll
- Blockchain
- Cryptocurrency
- Streaming Payments
- Web3
- DeFi
- SDK
- Stablecoins
- Solana
- Cards
---
