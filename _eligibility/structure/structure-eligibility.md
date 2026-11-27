---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    text: The Site is made available to users in the USA, EU/EEA, UK , and elsewhere except where prohibited by applicable law and sanctions.
  entity_types:
  - text: You must be 18 years or older to use the Site.
    type: individual
  minimum_age:
    text: You must be 18 years or older to use the Site.
    value: '18'
  restricted_uses:
  - summary: Sanctions and export-control violations
    text: will not use the Site contrary to applicable export-control or sanctions laws
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The public documentation can be browsed without creating a Structure account, connecting a wallet, connecting a trading account, completing KYC, providing private keys, or providing trading credentials.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Structure
provenance_date: '2026-11-10'
provider_name: Structure
provider_slug: structure
slug: structure-eligibility
source_date: '2026-11-10'
source_filename: structure-eligibility.yml
source_heading: Eligibility
source_page: https://structure.fi/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Structure\naid: structure\nurl: https://structure.fi/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  excluded: []\n  text: The Site is made available to users in the USA, EU/EEA, UK , and elsewhere except where prohibited by applicable\n    law and sanctions.\nentity_types:\n- type: individual\n  text: You must be 18 years or older to use the Site.\nrestricted_uses:\n- summary: Sanctions and export-control violations\n  text: will not use the Site contrary to applicable export-control or sanctions laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The public\
  \ documentation can be browsed without creating a Structure account, connecting a wallet, connecting\n    a trading account, completing KYC, providing private keys, or providing trading credentials.\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to use the Site.\n"
source_yaml_url: https://artifacts.apis.io/structure/eligibility/structure-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Structure's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Cryptocurrency
- DeFi
- Algorithmic Trading
- Web3
- Blockchain
- Trading
---
