---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Website on behalf of a legal entity, you also represent and warrant that
    type: business
  minimum_age:
    text: are of legal age to enter into a binding agreement
    value: legal age
  restricted_uses:
  - summary: Prior bans or suspensions
    text: have not been previously banned, suspended, or otherwise prohibited from using Our Services
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
name: Iron Fish
provenance_date: '2026-11-09'
provider_name: Iron Fish
provider_slug: iron-fish
slug: iron-fish-eligibility
source_date: '2026-11-09'
source_filename: iron-fish-eligibility.yml
source_heading: Eligibility
source_page: https://ironfish.network/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Iron Fish\naid: iron-fish\nurl: https://ironfish.network/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Website on behalf of a legal entity, you also represent and warrant that\nrestricted_uses:\n- summary: Prior bans or suspensions\n  text: have not been previously banned, suspended, or otherwise prohibited from using Our Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: are of legal age to enter into a binding\
  \ agreement\n"
source_yaml_url: https://artifacts.apis.io/iron-fish/eligibility/iron-fish-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Iron Fish's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Cryptocurrency
- Privacy
- Zero Knowledge
- Layer 1
- Web3
- RPC
- Wallets
---
