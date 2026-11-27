---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: may not be located in or a resident of any banned jurisdiction as determined by us in our discretion
  entity_types:
  - text: You must be at least 18 years of age to use the Services or participate in the Program
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use the Services or participate in the Program
    value: '18'
  restricted_uses:
  - summary: Illegal activity
    text: Use our Services to pay for, support or otherwise engage in any illegal activities, including, but not limited to illegal gambling, fraud, money-laundering, or terrorist activities.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: We may require eligibility verification, sanctions screening, and, where applicable, identity checks (KYC/KYB) before enabling certain features
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ETHGas
provenance_date: '2026-11-09'
provider_name: ETHGas
provider_slug: ethgas
slug: ethgas-eligibility
source_date: '2026-11-09'
source_filename: ethgas-eligibility.yml
source_heading: Eligibility
source_page: https://ethgas.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ETHGas\naid: ethgas\nurl: https://ethgas.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: may not be located in or a resident of any banned jurisdiction as determined by us in our discretion\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use the Services or participate in the Program\nrestricted_uses:\n- summary: Illegal activity\n  text: Use our Services to pay for, support or otherwise engage in any illegal activities, including, but not limited\n    to illegal gambling, fraud, money-laundering, or terrorist activities.\n\
  verification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: We may require eligibility verification, sanctions screening, and, where applicable, identity checks (KYC/KYB)\n    before enabling certain features\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Services or participate in the Program\n"
source_yaml_url: https://artifacts.apis.io/ethgas/eligibility/ethgas-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from ETHGas's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Infrastructure
- Blockchain
- Ethereum
- Trading
- Preconfirmations
- Blockspace
- MEV
- DeFi
- Web3
---
