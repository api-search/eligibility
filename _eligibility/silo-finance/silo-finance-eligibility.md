---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - LY
    - SO
    - SD
    - SY
    served: []
    text: THE SERVICES ARE NOT OFFERED TO PERSONS OR ENTITIES WHO RESIDE IN, ARE CITIZENS OF, ARE LOCATED IN ... THE CRIMEA REGION, CUBA, DONETSK, IRAN, LIBYA, NORTH KOREA, SOMALIA, SUDAN, SYRIA, (2) ANY OTHER COUNTRY TO WHICH THE UNITED STATES, THE UNITED KINGDOM, THE EUROPEAN UNION OR ANY OTHER JURISDICTION EMBARGOES GOODS
  entity_types:
  - text: The Services are offered and available to users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: The Services are offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Restricted jurisdictions and persons
    text: IF YOU ARE A RESTRICTED PERSON, THEN DO NOT USE OR ATTEMPT TO USE THE SERVICES.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- LY
- SO
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Silo Finance
provenance_date: '2026-11-10'
provider_name: Silo Finance
provider_slug: silo-finance
slug: silo-finance-eligibility
source_date: '2026-11-10'
source_filename: silo-finance-eligibility.yml
source_heading: Eligibility
source_page: https://www.silo.finance/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Silo Finance\naid: silo-finance\nurl: https://www.silo.finance/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - LY\n  - SO\n  - SD\n  - SY\n  text: THE SERVICES ARE NOT OFFERED TO PERSONS OR ENTITIES WHO RESIDE IN, ARE CITIZENS OF, ARE LOCATED IN ... THE\n    CRIMEA REGION, CUBA, DONETSK, IRAN, LIBYA, NORTH KOREA, SOMALIA, SUDAN, SYRIA, (2) ANY OTHER COUNTRY TO WHICH\n    THE UNITED STATES, THE UNITED KINGDOM, THE EUROPEAN UNION OR ANY OTHER JURISDICTION EMBARGOES GOODS\nentity_types:\n- type: individual\n  text: The Services are offered\
  \ and available to users who are 18 years of age or older.\nrestricted_uses:\n- summary: Restricted jurisdictions and persons\n  text: IF YOU ARE A RESTRICTED PERSON, THEN DO NOT USE OR ATTEMPT TO USE THE SERVICES.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are offered and available to users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/silo-finance/eligibility/silo-finance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Silo Finance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- DeFi
- Lending
- Money Markets
- Ethereum
- Smart Contracts
- Blockchain
- Web3
---
