---
api_specs:
- filename: pancakeswap-leaderboard-api-openapi.yml
  format: yaml
  label: PancakeSwap Leaderboard API
  slug: pancakeswap-leaderboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pancakeswap/openapi/pancakeswap-leaderboard-api-openapi.yml
- filename: pancakeswap-miscellaneous-api-openapi.yml
  format: yaml
  label: PancakeSwap Miscellaneous API
  slug: pancakeswap-miscellaneous-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pancakeswap/openapi/pancakeswap-miscellaneous-api-openapi.yml
- filename: pancakeswap-pairs-api-openapi.yml
  format: yaml
  label: PancakeSwap Pairs API
  slug: pancakeswap-pairs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pancakeswap/openapi/pancakeswap-pairs-api-openapi.yml
- filename: pancakeswap-summary-api-openapi.yml
  format: yaml
  label: PancakeSwap Summary API
  slug: pancakeswap-summary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pancakeswap/openapi/pancakeswap-summary-api-openapi.yml
- filename: pancakeswap-tokens-api-openapi.yml
  format: yaml
  label: PancakeSwap Tokens API
  slug: pancakeswap-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pancakeswap/openapi/pancakeswap-tokens-api-openapi.yml
- filename: pancakeswap-users-api-openapi.yml
  format: yaml
  label: PancakeSwap Users API
  slug: pancakeswap-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pancakeswap/openapi/pancakeswap-users-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - BY
    - CU
    - CD
    - IR
    - IQ
    - NZ
    - KP
    - SS
    - SD
    - SY
    - US
    - ZW
    served: []
    text: 'You represent that you are not a user from the following countries or regions when participating in our Initial Farm Offerings: Belarus, Cuba, Crimea Region, Democratic Republic of Congo, Iran, Iraq, New Zealand, North Korea, South Sudan, Sudan, Syria, United States of America and its territories (American Samoa, Guam, Puerto Rico, the Northern Mariana Islands, and the U.S. Virgin Islands), Zimbabwe.'
  entity_types:
  - text: you are at least the age of majority in your jurisdiction (e.g., 18 years old in the United States)
    type: individual
  - text: on behalf of yourself and any company or legal entity for which you may access or use the Website.
    type: business
  minimum_age:
    text: you are at least the age of majority in your jurisdiction (e.g., 18 years old in the United States)
    value: age of majority
  restricted_uses:
  - summary: Sanctioned persons
    text: You further represent that you are not (a) the subject of economic or trade sanctions administered or enforced by any governmental authority
  - summary: Illegal activity
    text: you will not access or use the Website to conduct, promote, or otherwise facilitate any illegal activity.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- BY
- CU
- CD
- IR
- IQ
- NZ
- KP
- SS
- SD
- SY
- US
- ZW
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PancakeSwap
provenance_date: '2026-11-10'
provider_name: PancakeSwap
provider_slug: pancakeswap
slug: pancakeswap-eligibility
source_date: '2026-11-10'
source_filename: pancakeswap-eligibility.yml
source_heading: Eligibility
source_page: https://pancakeswap.finance/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PancakeSwap\naid: pancakeswap\nurl: https://pancakeswap.finance/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - BY\n  - CU\n  - CD\n  - IR\n  - IQ\n  - NZ\n  - KP\n  - SS\n  - SD\n  - SY\n  - US\n  - ZW\n  text: 'You represent that you are not a user from the following countries or regions when participating in our\n    Initial Farm Offerings: Belarus, Cuba, Crimea Region, Democratic Republic of Congo, Iran, Iraq, New Zealand,\n    North Korea, South Sudan, Sudan, Syria, United States of America and its territories (American Samoa, Guam,\n    Puerto Rico, the Northern Mariana\
  \ Islands, and the U.S. Virgin Islands), Zimbabwe.'\nentity_types:\n- type: individual\n  text: you are at least the age of majority in your jurisdiction (e.g., 18 years old in the United States)\n- type: business\n  text: on behalf of yourself and any company or legal entity for which you may access or use the Website.\nrestricted_uses:\n- summary: Sanctioned persons\n  text: You further represent that you are not (a) the subject of economic or trade sanctions administered or enforced\n    by any governmental authority\n- summary: Illegal activity\n  text: you will not access or use the Website to conduct, promote, or otherwise facilitate any illegal activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you are at least the age of majority in your jurisdiction (e.g., 18 years old in the United States)\n"
source_yaml_url: https://artifacts.apis.io/pancakeswap/eligibility/pancakeswap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from PancakeSwap's own page on 2026-11-10.
synthetic: false
tags:
- DeFi
- Decentralized Exchange
- BNB Chain
- Blockchain
- Swap
- Liquidity
- Yield Farming
- NFT
- Web3
---
