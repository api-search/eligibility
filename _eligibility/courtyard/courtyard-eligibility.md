---
claim_count: 8
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: (currently, Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk People’s Republic, and Luhansk People’s Republic regions of Ukraine)
  entity_types:
  - text: You must be eighteen (18) years old or otherwise capable of forming a binding contract in your jurisdiction to use the Service.
    type: individual
  - text: if you are an entity, conflict with or violate any of the charter documents of such entity
    type: business
  minimum_age:
    text: You must be eighteen (18) years old or otherwise capable of forming a binding contract in your jurisdiction to use the Service.
    value: '18'
  restricted_uses:
  - summary: Financial activities requiring registration or licensing
    text: Use the Service to carry out any financial activities subject to registration or licensing
  - summary: Fundraising for a business, protocol or platform
    text: Use the Service to participate in fundraising for a business, protocol, or platform
  - summary: Use of Service data for direct marketing
    text: Use data collected from our Service for any direct marketing activity
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: As a precondition of any transfer of the associated Asset, Courtyard shall verify (i) your identity, (ii) your compliance with this Agreement and eligibility to use the Service
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
name: Courtyard
provenance_date: '2026-11-09'
provider_name: Courtyard
provider_slug: courtyard
slug: courtyard-eligibility
source_date: '2026-11-09'
source_filename: courtyard-eligibility.yml
source_heading: Eligibility
source_page: https://docs.courtyard.io/courtyard/logistics-and-legal/user-agreements/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Courtyard\naid: courtyard\nurl: https://docs.courtyard.io/courtyard/logistics-and-legal/user-agreements/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: (currently, Cuba, Iran, North Korea, Syria, and the Crimea, Donetsk People’s Republic, and Luhansk People’s\n    Republic regions of Ukraine)\nentity_types:\n- type: individual\n  text: You must be eighteen (18) years old or otherwise capable of forming a binding contract in your jurisdiction\n    to use the Service.\n- type: business\n  text: if you are an entity, conflict\
  \ with or violate any of the charter documents of such entity\nrestricted_uses:\n- summary: Financial activities requiring registration or licensing\n  text: Use the Service to carry out any financial activities subject to registration or licensing\n- summary: Fundraising for a business, protocol or platform\n  text: Use the Service to participate in fundraising for a business, protocol, or platform\n- summary: Use of Service data for direct marketing\n  text: Use data collected from our Service for any direct marketing activity\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: As a precondition of any transfer of the associated Asset, Courtyard shall verify (i) your identity, (ii)\n    your compliance with this Agreement and eligibility to use the Service\nminimum_age:\n  value: '18'\n  text: You must be eighteen (18) years old or otherwise capable of forming a binding contract in your jurisdiction\n    to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/courtyard/eligibility/courtyard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 8 quoted statements, read from Courtyard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Commerce
- Collectibles
- Marketplace
- Tokenization
- NFT
- Blockchain
- Web3
---
