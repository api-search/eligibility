---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “you” or “your” means the individual user interacting with our Services, or if such user is below the minimum legal age of adulthood in their country of residence (“Minor”), the user’s parent or legal guardian
    type: individual
  minimum_age:
    text: if such user is below the minimum legal age of adulthood in their country of residence (“Minor”), the user’s parent or legal guardian entering into this Agreement on their behalf
    value: null
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You agree not to use, export, re-export, download, or otherwise transfer any part of the Services, Virtual Items, or your Account into (or to a national or resident of) any country to which the U.S. has embargoed goods
  - summary: Lawful use only; no wagering
    text: You will only use the Services for lawful purposes, in compliance with applicable laws.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: To create an Account, you may be asked to provide your age information and country/region, and then provide an email address, a username, a password
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Rockstar Games
provenance_date: '2026-11-10'
provider_name: Rockstar Games
provider_slug: rockstar-games
slug: rockstar-games-eligibility
source_date: '2026-11-10'
source_filename: rockstar-games-eligibility.yml
source_heading: Eligibility
source_page: https://www.rockstargames.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rockstar Games\naid: rockstar-games\nurl: https://www.rockstargames.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “you” or “your” means the individual user interacting with our Services, or if such user is below the minimum\n    legal age of adulthood in their country of residence (“Minor”), the user’s parent or legal guardian\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You agree not to use, export, re-export, download, or otherwise transfer any part of the Services, Virtual\n\
  \    Items, or your Account into (or to a national or resident of) any country to which the U.S. has embargoed goods\n- summary: Lawful use only; no wagering\n  text: You will only use the Services for lawful purposes, in compliance with applicable laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: To create an Account, you may be asked to provide your age information and country/region, and then provide\n    an email address, a username, a password\nminimum_age:\n  value: null\n  text: if such user is below the minimum legal age of adulthood in their country of residence (“Minor”), the user’s\n    parent or legal guardian entering into this Agreement on their behalf\n"
source_yaml_url: https://artifacts.apis.io/rockstar-games/eligibility/rockstar-games-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Rockstar Games's own page on 2026-11-10.
synthetic: false
tags:
- Gaming
- Entertainment
- Video Games
- Grand Theft Auto
- Red Dead Redemption
- Identity
- OAuth
- Authentication
---
