---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: you are a citizen or resident of the United States of America or Canada and that you have an address in the United States of America or Canada
  entity_types:
  - text: you are 18 years of age (or the minimum age in your state of residence, which may also be 19 or 21) or older
    type: individual
  minimum_age:
    text: you are 18 years of age (or the minimum age in your state of residence, which may also be 19 or 21) or older
    value: '18'
  restricted_uses:
  - summary: Sports league participants barred
    text: All leagues or associations on which Underdog offers contests including but not limited to NFL, NBA, MLB, NHL, PGA, and NCAA (collectively, “League and Association”), and any athletes, coaches and other team management, team support personnel (e.g., without limitation, team physicians) and team owners of any League and Association may not participate in any Underdog Fantasy Contests.
  - summary: Employees limited to testing
    text: Underdog employees may only use the Services for the purpose of testing the user experience.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: By creating an Underdog Account, you agree to provide us with a valid mailing address, date of birth, and Social Security number as well as any other information we may require in order to run appropriate identity checks
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Underdog Fantasy
provenance_date: '2026-11-10'
provider_name: Underdog Fantasy
provider_slug: underdog-fantasy
slug: underdog-fantasy-eligibility
source_date: '2026-11-10'
source_filename: underdog-fantasy-eligibility.yml
source_heading: Eligibility
source_page: https://legal.underdogsports.com/#terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Underdog Fantasy\naid: underdog-fantasy\nurl: https://legal.underdogsports.com/#terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: you are a citizen or resident of the United States of America or Canada and that you have an address in\n    the United States of America or Canada\nentity_types:\n- type: individual\n  text: you are 18 years of age (or the minimum age in your state of residence, which may also be 19 or 21) or older\nrestricted_uses:\n- summary: Sports league participants barred\n  text: All leagues or associations on which Underdog\
  \ offers contests including but not limited to NFL, NBA, MLB,\n    NHL, PGA, and NCAA (collectively, “League and Association”), and any athletes, coaches and other team management,\n    team support personnel (e.g., without limitation, team physicians) and team owners of any League and Association\n    may not participate in any Underdog Fantasy Contests.\n- summary: Employees limited to testing\n  text: Underdog employees may only use the Services for the purpose of testing the user experience.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: By creating an Underdog Account, you agree to provide us with a valid mailing address, date of birth, and\n    Social Security number as well as any other information we may require in order to run appropriate identity\n    checks\nminimum_age:\n  value: '18'\n  text: you are 18 years of age (or the minimum age in your state of residence, which may also be 19 or 21) or older\n"
source_yaml_url: https://artifacts.apis.io/underdog-fantasy/eligibility/underdog-fantasy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Underdog Fantasy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Fantasy Sports
- Sports Betting
- Prediction Markets
- Gaming
- Entertainment
- Consumer
- Mobile
---
