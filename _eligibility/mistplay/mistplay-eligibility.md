---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'You may not use Mistplay’s Services if you: i) are located in a country that is subject to embargo by the U.S. or other similar authority (“Sanctioned Country”)'
  entity_types:
  - text: Access your account for any purpose other than personal use and not for any business or commercial purpose.
    type: individual
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No business or commercial use of accounts
    text: Access your account for any purpose other than personal use and not for any business or commercial purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Mistplay may require you to complete identity, account, device, location, or eligibility verification before or after registration
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mistplay
provenance_date: '2026-11-10'
provider_name: Mistplay
provider_slug: mistplay
slug: mistplay-eligibility
source_date: '2026-11-10'
source_filename: mistplay-eligibility.yml
source_heading: Eligibility
source_page: https://www.mistplay.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mistplay\naid: mistplay\nurl: https://www.mistplay.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: 'You may not use Mistplay’s Services if you: i) are located in a country that is subject to embargo by the\n    U.S. or other similar authority (“Sanctioned Country”)'\nentity_types:\n- type: individual\n  text: Access your account for any purpose other than personal use and not for any business or commercial purpose.\nrestricted_uses:\n- summary: No business or commercial use of accounts\n  text: Access your account for any purpose other than\
  \ personal use and not for any business or commercial purpose.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Mistplay may require you to complete identity, account, device, location, or eligibility verification before\n    or after registration\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/mistplay/eligibility/mistplay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Mistplay's own page on 2026-11-10.
synthetic: false
tags:
- Gaming
- Rewards
- Mobile
- Gift Cards
- Company
---
