---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'To participate in an Auction, you must: Be at least 18 years old Be legally capable of entering into binding contracts'
    type: individual
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Speculative resale
    text: Avant Arte reserves the right to disqualify any participant from the Draw or to refuse any entry at our sole discretion.
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
name: Avant Arte
provenance_date: '2026-11-09'
provider_name: Avant Arte
provider_slug: avant-arte
slug: avant-arte-eligibility
source_date: '2026-11-09'
source_filename: avant-arte-eligibility.yml
source_heading: Eligibility
source_page: https://avantarte.com/support/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Avant Arte\naid: avant-arte\nurl: https://avantarte.com/support/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'To participate in an Auction, you must: Be at least 18 years old Be legally capable of entering into binding\n    contracts'\nrestricted_uses:\n- summary: Speculative resale\n  text: Avant Arte reserves the right to disqualify any participant from the Draw or to refuse any entry at our\n    sole discretion.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/avant-arte/eligibility/avant-arte-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Avant Arte's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Marketplace
- Art
- E-Commerce
- Collectibles
- Contemporary Art
- Print
---
