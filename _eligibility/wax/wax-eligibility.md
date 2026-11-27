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
    text: you are not located in, and are not a national or resident of, any country or territory subject to territorial embargoes of the United States, United Kingdom, European Union, Australia or Canada, including Cuba, Iran, North Korea, Syria
  entity_types:
  - text: You must be at least 18 years of age or qualify as an adult in your country of residence to use the WAX Cloud Wallet
    type: individual
  minimum_age:
    text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO USE OUR OFFERINGS REGARDLESS OF ANY CONSENT FROM YOUR PARENT OR GUARDIAN.
    value: '18'
  restricted_uses:
  - summary: Sanctioned or restricted parties
    text: you are not a person or entity, or owned by, under the control of, or affiliated with, a person or entity (i) identified on U.S. or other applicable government restricted party lists
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
name: WAX
provenance_date: '2026-11-10'
provider_name: WAX
provider_slug: wax
slug: wax-eligibility
source_date: '2026-11-10'
source_filename: wax-eligibility.yml
source_heading: Eligibility
source_page: https://www.waxp.io/wcw-tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: WAX\naid: wax\nurl: https://www.waxp.io/wcw-tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: you are not located in, and are not a national or resident of, any country or territory subject to territorial\n    embargoes of the United States, United Kingdom, European Union, Australia or Canada, including Cuba, Iran, North\n    Korea, Syria\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age or qualify as an adult in your country of residence to use the WAX\n    Cloud Wallet\nrestricted_uses:\n- summary: Sanctioned or restricted\
  \ parties\n  text: you are not a person or entity, or owned by, under the control of, or affiliated with, a person or entity\n    (i) identified on U.S. or other applicable government restricted party lists\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MUST BE AT LEAST 18 YEARS OF AGE TO USE OUR OFFERINGS REGARDLESS OF ANY CONSENT FROM YOUR PARENT OR\n    GUARDIAN.\n"
source_yaml_url: https://artifacts.apis.io/wax/eligibility/wax-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from WAX's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Blockchain
- NFT
- Web3
- Gaming
- Antelope
- Wallets
---
