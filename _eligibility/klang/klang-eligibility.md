---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to register an Account.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to register an Account.
    value: '16'
  restricted_uses:
  - summary: No real-money trading or external markets
    text: You must not create, use, promote, facilitate or participate in any unauthorised external market
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Publisher may verify Your age and delete Your Account if You fail to verify Your age.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Klang Games
provenance_date: '2026-11-09'
provider_name: Klang Games
provider_slug: klang
slug: klang-eligibility
source_date: '2026-11-09'
source_filename: klang-eligibility.yml
source_heading: Eligibility
source_page: https://seed.game/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klang Games\naid: klang\nurl: https://seed.game/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to register an Account.\nrestricted_uses:\n- summary: No real-money trading or external markets\n  text: You must not create, use, promote, facilitate or participate in any unauthorised external market\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Publisher may verify Your age and delete Your Account if You fail to verify Your age.\nminimum_age:\n\
  \  value: '16'\n  text: You must be at least 16 years old to register an Account.\n"
source_yaml_url: https://artifacts.apis.io/klang/eligibility/klang-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Klang Games's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Gaming
- Game Development
- MMO
- Simulation
- Entertainment
- Identity
- Berlin
---
