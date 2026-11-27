---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: 'The Services are offered and available to users who are 18 years of age or older, and reside in the United States or any of its territories or possessions, except for residents of the following states:'
  entity_types:
  - text: The Services are offered and available to users who are 18 years of age or older
    type: individual
  minimum_age:
    text: The Services are offered and available to users who are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: State age rule for Matches
    text: you must be at least the minimum legal age required by the state in which you reside in order to enter into such Matches.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: To comply with legal and regulatory obligations, we may request additional documents (e.g., government-issued photo ID, proof of address, proof of ownership of the payment method) before processing withdrawals.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Players Lounge
provenance_date: '2026-11-10'
provider_name: Players Lounge
provider_slug: players-lounge
slug: players-lounge-eligibility
source_date: '2026-11-10'
source_filename: players-lounge-eligibility.yml
source_heading: Eligibility
source_page: https://www.playerslounge.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Players Lounge\naid: players-lounge\nurl: https://www.playerslounge.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: 'The Services are offered and available to users who are 18 years of age or older, and reside in the United\n    States or any of its territories or possessions, except for residents of the following states:'\nentity_types:\n- type: individual\n  text: The Services are offered and available to users who are 18 years of age or older\nrestricted_uses:\n- summary: State age rule for Matches\n  text: you must be at least the minimum legal\
  \ age required by the state in which you reside in order to enter into\n    such Matches.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: To comply with legal and regulatory obligations, we may request additional documents (e.g., government-issued\n    photo ID, proof of address, proof of ownership of the payment method) before processing withdrawals.\nminimum_age:\n  value: '18'\n  text: The Services are offered and available to users who are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/players-lounge/eligibility/players-lounge-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Players Lounge's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Esports
- Skill-Based Gaming
- Money Matches
- Player Staking
- Consumer
- Video Games
---
