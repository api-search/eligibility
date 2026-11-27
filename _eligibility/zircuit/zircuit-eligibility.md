---
api_specs:
- filename: zircuit-orders-api-openapi.yml
  format: yaml
  label: Zircuit Orders API
  slug: zircuit-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zircuit/openapi/zircuit-orders-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - DZ
    - BD
    - BO
    - BY
    - BI
    - MM
    - CI
    - CU
    - CD
    - EC
    - IR
    - IQ
    - LR
    - LY
    - ML
    - MA
    - NP
    - KP
    - SO
    - SD
    - SY
    - US
    - VE
    - YE
    - ZW
    - RU
    - UA
    served: []
    text: Morocco,Nepal,NorthKorea,Somalia,Sudan,Syria,United States, Venezuela, Yemen, Zimbabwe
  entity_types:
  - text: at least 18yearsofage
    type: individual
  minimum_age:
    text: at least 18yearsofage
    value: '18'
  restricted_uses:
  - summary: Circumventing territorial restrictions
    text: THERESTRICTIONSSETFORTHHEREINISPROHIBITED
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- DZ
- BD
- BO
- BY
- BI
- MM
- CI
- CU
- CD
- EC
- IR
- IQ
- LR
- LY
- ML
- MA
- NP
- KP
- SO
- SD
- SY
- US
- VE
- YE
- ZW
- RU
- UA
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Zircuit
provenance_date: '2026-11-10'
provider_name: Zircuit
provider_slug: zircuit
slug: zircuit-eligibility
source_date: '2026-11-10'
source_filename: zircuit-eligibility.yml
source_heading: Eligibility
source_page: https://static.zircuit.com/docs/tos.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zircuit\naid: zircuit\nurl: https://static.zircuit.com/docs/tos.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - DZ\n  - BD\n  - BO\n  - BY\n  - BI\n  - MM\n  - CI\n  - CU\n  - CD\n  - EC\n  - IR\n  - IQ\n  - LR\n  - LY\n  - ML\n  - MA\n  - NP\n  - KP\n  - SO\n  - SD\n  - SY\n  - US\n  - VE\n  - YE\n  - ZW\n  - RU\n  - UA\n  text: Morocco,Nepal,NorthKorea,Somalia,Sudan,Syria,United States, Venezuela, Yemen, Zimbabwe\nentity_types:\n- type: individual\n  text: at least 18yearsofage\nrestricted_uses:\n- summary: Circumventing territorial restrictions\n  text: THERESTRICTIONSSETFORTHHEREINISPROHIBITED\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least 18yearsofage\n"
source_yaml_url: https://artifacts.apis.io/zircuit/eligibility/zircuit-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Zircuit's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Blockchain
- Layer 2
- Rollup
- Zero Knowledge
- EVM
- DeFi
- JSON-RPC
- Web3
---
