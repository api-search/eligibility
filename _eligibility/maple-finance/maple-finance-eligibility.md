---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - UA
    - IR
    - KP
    - CU
    - SY
    - SD
    served: []
    text: The User must not use the Interface if the User is a citizen or resident of or are otherwise accessing the Interface from the Crimea, Donetsk, or Luhansk regions of Ukraine or the nations of Iran, North Korea, Cuba, Syria, Sudan
  entity_types:
  - text: This Interface is offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: This Interface is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful use only; no securities transactions requiring registration
    text: Use the Interface to execute any transactions that may be considered a securities transaction or otherwise requires registration with the Securities and Exchange Commission
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- UA
- IR
- KP
- CU
- SY
- SD
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Maple Finance
provenance_date: '2026-11-10'
provider_name: Maple Finance
provider_slug: maple-finance
slug: maple-finance-eligibility
source_date: '2026-11-10'
source_filename: maple-finance-eligibility.yml
source_heading: Eligibility
source_page: https://docs.maple.finance/legal/interface-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Maple Finance\naid: maple-finance\nurl: https://docs.maple.finance/legal/interface-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - UA\n  - IR\n  - KP\n  - CU\n  - SY\n  - SD\n  text: The User must not use the Interface if the User is a citizen or resident of or are otherwise accessing the\n    Interface from the Crimea, Donetsk, or Luhansk regions of Ukraine or the nations of Iran, North Korea, Cuba,\n    Syria, Sudan\nentity_types:\n- type: individual\n  text: This Interface is offered and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Lawful\
  \ use only; no securities transactions requiring registration\n  text: Use the Interface to execute any transactions that may be considered a securities transaction or otherwise\n    requires registration with the Securities and Exchange Commission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Interface is offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/maple-finance/eligibility/maple-finance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Maple Finance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Defi Lending
- DeFi
- Onchain Asset Management
- Institutional Lending
- Stablecoin Yield
- Ethereum
- SDK
- MCP
---
