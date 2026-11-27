---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - SG
    text: You are in Singapore
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal activities
    text: you are using the Platform for any illegal activities or where we have reasonable suspicion that you may be doing so
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
name: StashAway
provenance_date: '2026-11-10'
provider_name: StashAway
provider_slug: stashaway
slug: stashaway-eligibility
source_date: '2026-11-10'
source_filename: stashaway-eligibility.yml
source_heading: Eligibility
source_page: https://www.stashaway.sg/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StashAway\naid: stashaway\nurl: https://www.stashaway.sg/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SG\n  excluded: []\n  text: You are in Singapore\nentity_types: []\nrestricted_uses:\n- summary: Illegal activities\n  text: you are using the Platform for any illegal activities or where we have reasonable suspicion that you may\n    be doing so\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/stashaway/eligibility/stashaway-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from StashAway's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Wealth Management
- Investing
- Robo-Advisor
- Financial Services
- Asset Management
- ETFs
- Cash Management
- Fintech
- Singapore
- Private Markets
---
