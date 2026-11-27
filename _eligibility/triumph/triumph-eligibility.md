---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Triumph restricts all real money gameplay to locations in which Triumph believes it is allowed to operate real money Tournaments
  entity_types:
  - text: your account is held by a natural person and not for the benefit of any company or entity.
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years old (for real-money play), and at least thirteen (13) years old for free-play
    value: '18'
  restricted_uses:
  - summary: Real-money play only from eligible locations
    text: Use of and/or access to the Platform to participate in a real-money Tournament from any location that is not an Eligible Location is strictly prohibited.
  - summary: No commercial endeavors without approval
    text: you shall not use the Platform in connection with any commercial endeavors except those that are specifically endorsed or approved by Triumph
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
name: Triumph
provenance_date: '2026-11-10'
provider_name: Triumph
provider_slug: triumph
slug: triumph-eligibility
source_date: '2026-11-10'
source_filename: triumph-eligibility.yml
source_heading: Eligibility
source_page: https://docs.triumpharcade.com/terms-of-use-triumph-arcade
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Triumph\naid: triumph\nurl: https://docs.triumpharcade.com/terms-of-use-triumph-arcade\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Triumph restricts all real money gameplay to locations in which Triumph believes it is allowed to operate\n    real money Tournaments\nentity_types:\n- type: individual\n  text: your account is held by a natural person and not for the benefit of any company or entity.\nrestricted_uses:\n- summary: Real-money play only from eligible locations\n  text: Use of and/or access to the Platform to participate in a real-money Tournament\
  \ from any location that is\n    not an Eligible Location is strictly prohibited.\n- summary: No commercial endeavors without approval\n  text: you shall not use the Platform in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by Triumph\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old (for real-money play), and at least thirteen (13) years old for\n    free-play\n"
source_yaml_url: https://artifacts.apis.io/triumph/eligibility/triumph-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Triumph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Gaming
- Real-Money Gaming
- Tournaments
- Mobile Games
- SDK
- Payments
- Collectibles
---
