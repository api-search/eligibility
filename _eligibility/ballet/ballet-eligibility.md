---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accessing the Services on behalf of an entity (for example, a company, non-profit entity, university, or other business or organization), you represent to us that you have authority to bind that entity to these terms
    type: business
  minimum_age:
    text: 'you warrant and certify to us that: (i) you are at least 18-years old'
    value: '18'
  restricted_uses:
  - summary: Investment solicitations
    text: Offer or otherwise facilitate through the Services any investment opportunities, solicitations, chain letters, pyramid schemes
  - summary: Mining cryptocurrency
    text: you may not mine a cryptocurrency or otherwise utilize large computational power from the Services without our express and specific approval in writing
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
name: Ballet
provenance_date: '2026-11-09'
provider_name: Ballet
provider_slug: ballet
slug: ballet-eligibility
source_date: '2026-11-09'
source_filename: ballet-eligibility.yml
source_heading: Eligibility
source_page: https://www.ballet.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ballet\naid: ballet\nurl: https://www.ballet.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accessing the Services on behalf of an entity (for example, a company, non-profit entity, university,\n    or other business or organization), you represent to us that you have authority to bind that entity to these\n    terms\nrestricted_uses:\n- summary: Investment solicitations\n  text: Offer or otherwise facilitate through the Services any investment opportunities, solicitations, chain letters,\n    pyramid schemes\n\
  - summary: Mining cryptocurrency\n  text: you may not mine a cryptocurrency or otherwise utilize large computational power from the Services without\n    our express and specific approval in writing\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'you warrant and certify to us that: (i) you are at least 18-years old'\n"
source_yaml_url: https://artifacts.apis.io/ballet/eligibility/ballet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ballet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Wallets
- Cold Storage
- Bitcoin
- Hardware Wallet
- Self-Custody
---
