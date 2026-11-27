---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a terrorist-supporting country
  entity_types:
  - text: You may not create or use a Game Account or use or access any of our Services on behalf of a legal entity or for a commercial purpose
    type: individual
  minimum_age:
    text: you must be above the minimum age to consent for data collection in your jurisdiction (e.g., 13 or older in the United States, 16 or older in some EU countries)
    value: '13'
  restricted_uses:
  - summary: No commercial use
    text: use them commercially, for a promotional purpose, or for the benefit of any third party
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
name: Faraway
provenance_date: '2026-11-09'
provider_name: Faraway
provider_slug: faraway
slug: faraway-eligibility
source_date: '2026-11-09'
source_filename: faraway-eligibility.yml
source_heading: Eligibility
source_page: https://faraway.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Faraway\naid: faraway\nurl: https://faraway.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent and warrant that (i) you are not located in a country that is subject to a U.S. Government\n    embargo, or that has been designated by the U.S. Government as a terrorist-supporting country\nentity_types:\n- type: individual\n  text: You may not create or use a Game Account or use or access any of our Services on behalf of a legal entity\n    or for a commercial purpose\nrestricted_uses:\n- summary: No commercial use\n  text: use them commercially, for a promotional\
  \ purpose, or for the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you must be above the minimum age to consent for data collection in your jurisdiction (e.g., 13 or older\n    in the United States, 16 or older in some EU countries)\n"
source_yaml_url: https://artifacts.apis.io/faraway/eligibility/faraway-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Faraway's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Web3
- Blockchain
- Gaming Economy
- Player Identity
- Marketplace
- Creator Platform
- NFT
- Developer Platform
---
