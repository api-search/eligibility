---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not a citizen or resident of a state, country, territory or other jurisdiction that is embargoed by Switzerland
  entity_types:
  - text: you must be able to form a legally binding contract either on behalf of a company (or other legal entity) or as an individual
    type: individual
  - text: on behalf of a company (or other legal entity)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: you will only use the Services and the Website for lawful purposes and in accordance with these Terms
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
name: RLY Network
provenance_date: '2026-11-10'
provider_name: RLY Network
provider_slug: rly-network
slug: rly-network-eligibility
source_date: '2026-11-10'
source_filename: rly-network-eligibility.yml
source_heading: Eligibility
source_page: https://rly.network/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: RLY Network\naid: rly-network\nurl: https://rly.network/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not a citizen or resident of a state, country, territory or other jurisdiction that is embargoed\n    by Switzerland\nentity_types:\n- type: individual\n  text: you must be able to form a legally binding contract either on behalf of a company (or other legal entity)\n    or as an individual\n- type: business\n  text: on behalf of a company (or other legal entity)\nrestricted_uses:\n- summary: Lawful use only\n  text: you will only use the Services and the\
  \ Website for lawful purposes and in accordance with these Terms\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rly-network/eligibility/rly-network-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from RLY Network's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web3
- Blockchain
- Wallets
- Mobile SDK
- Gasless Transactions
- Cryptocurrency
- Developer Tools
---
