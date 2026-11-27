---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Users who are natural persons may only register if they are at least 18 years old and have unlimited legal capacity.
    type: individual
  minimum_age:
    text: Users who are natural persons may only register if they are at least 18 years old and have unlimited legal capacity.
    value: '18'
  restricted_uses:
  - summary: No acting for others
    text: The User may not act on behalf of another person.
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
name: Timeless
provenance_date: '2026-11-10'
provider_name: Timeless
provider_slug: timeless
slug: timeless-eligibility
source_date: '2026-11-10'
source_filename: timeless-eligibility.yml
source_heading: Eligibility
source_page: https://www.timeless.investments/en/general-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Timeless\naid: timeless\nurl: https://www.timeless.investments/en/general-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Users who are natural persons may only register if they are at least 18 years old and have unlimited legal\n    capacity.\nrestricted_uses:\n- summary: No acting for others\n  text: The User may not act on behalf of another person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users who are natural persons may only register\
  \ if they are at least 18 years old and have unlimited legal\n    capacity.\n"
source_yaml_url: https://artifacts.apis.io/timeless/eligibility/timeless-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Timeless's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Collectibles
- Alternative Assets
- Fractional Ownership
- Investing
- Mobile App
---
