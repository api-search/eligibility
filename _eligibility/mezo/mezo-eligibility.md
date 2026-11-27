---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - IR
    - CU
    - KP
    - SY
    - MM
    served: []
    text: you must not be a resident, citizen or agent of, or incorporated in, and do not have a registered office in Iran, Cuba, North Korea, Syria, Myanmar (Burma), the regions of Crimea, Donetsk or Luhansk, or any other country or region that is the subject of comprehensive country-wide or region-wide economic sanctions by the United States
  entity_types:
  - text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in which you reside
    type: individual
  minimum_age:
    text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Sanctioned persons
    text: you are not the subject of economic or trade sanctions administered or enforced by any governmental authority
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- CU
- KP
- SY
- MM
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mezo
provenance_date: '2026-11-10'
provider_name: Mezo
provider_slug: mezo
slug: mezo-eligibility
source_date: '2026-11-10'
source_filename: mezo-eligibility.yml
source_heading: Eligibility
source_page: https://mezo.org/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mezo\naid: mezo\nurl: https://mezo.org/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - IR\n  - CU\n  - KP\n  - SY\n  - MM\n  text: you must not be a resident, citizen or agent of, or incorporated in, and do not have a registered office\n    in Iran, Cuba, North Korea, Syria, Myanmar (Burma), the regions of Crimea, Donetsk or Luhansk, or any other\n    country or region that is the subject of comprehensive country-wide or region-wide economic sanctions by the\n    United States\nentity_types:\n- type: individual\n  text: if you are entering into these Terms\
  \ as an individual, then you are of legal age in the jurisdiction in\n    which you reside\nrestricted_uses:\n- summary: Sanctioned persons\n  text: you are not the subject of economic or trade sanctions administered or enforced by any governmental authority\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in\n    which you reside\n"
source_yaml_url: https://artifacts.apis.io/mezo/eligibility/mezo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mezo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web3
- Blockchain
- Bitcoin
- DeFi
- EVM
- Cosmos SDK
- Stablecoins
- JSON-RPC
- Layer 2
- Cryptocurrency
---
