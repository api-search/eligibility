---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement (“Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No life-critical or safety uses
    text: use any Pimlico IP for any activity where use or failure of the Pimlico IP could lead to death, personal injury, or environmental damage, including life support systems, emergency services, nuclear facilities, autonomous vehicles, or air traffic control
  - summary: No Sensitive Data storage
    text: Customer will not use the Platform to store Sensitive Data
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
name: Pimlico
provenance_date: '2026-11-10'
provider_name: Pimlico
provider_slug: pimlico
slug: pimlico-eligibility
source_date: '2026-11-10'
source_filename: pimlico-eligibility.yml
source_heading: Eligibility
source_page: https://www.pimlico.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pimlico\naid: pimlico\nurl: https://www.pimlico.io/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity on whose behalf the individual accepting this Agreement accepts this Agreement (“Customer”)\nrestricted_uses:\n- summary: No life-critical or safety uses\n  text: use any Pimlico IP for any activity where use or failure of the Pimlico IP could lead to death, personal\n    injury, or environmental damage, including life support systems, emergency services, nuclear facilities, autonomous\n    vehicles, or air traffic control\n\
  - summary: No Sensitive Data storage\n  text: Customer will not use the Platform to store Sensitive Data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pimlico/eligibility/pimlico-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Pimlico's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Account Abstraction
- ERC-4337
- Blockchain
- Ethereum
- Web3
- Paymaster
- Bundler
- Smart Accounts
- Gas Sponsorship
- Wallets
- Infrastructure
---
