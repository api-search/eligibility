---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You are not a resident, national, or agent of any country or region subject to comprehensive sanctions/embargoes imposed by the United States, the United Kingdom, the European Union, or other relevant authority (including, without limitation, Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine, as such lists may change).
  entity_types:
  - text: You are at least the legal age of majority in your jurisdiction and in any event at least 18 years old.
    type: individual
  minimum_age:
    text: You are at least the legal age of majority in your jurisdiction and in any event at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: No illegal or financial crime use
    text: You will not use the Services for any illegal, illicit, or prohibited activity (including money laundering, terrorist financing, sanctions evasion, market manipulation, fraud, or other financial crime).
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Freeport Markets
provenance_date: '2026-11-09'
provider_name: Freeport Markets
provider_slug: freeport-markets
slug: freeport-markets-eligibility
source_date: '2026-11-09'
source_filename: freeport-markets-eligibility.yml
source_heading: Eligibility
source_page: https://freeportmarkets.com/terms-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Freeport Markets\naid: freeport-markets\nurl: https://freeportmarkets.com/terms-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You are not a resident, national, or agent of any country or region subject to comprehensive sanctions/embargoes\n    imposed by the United States, the United Kingdom, the European Union, or other relevant authority (including,\n    without limitation, Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine,\n    as such lists may change).\nentity_types:\n- type: individual\n  text:\
  \ You are at least the legal age of majority in your jurisdiction and in any event at least 18 years old.\nrestricted_uses:\n- summary: No illegal or financial crime use\n  text: You will not use the Services for any illegal, illicit, or prohibited activity (including money laundering,\n    terrorist financing, sanctions evasion, market manipulation, fraud, or other financial crime).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least the legal age of majority in your jurisdiction and in any event at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/freeport-markets/eligibility/freeport-markets-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Freeport Markets's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Trading
- Cryptocurrency
- Fintech
- Investing
- DeFi
- Pre-IPO
- Web3
---
