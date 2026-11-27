---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: CartRevolt is run for people in the United States.
  entity_types:
  - text: You need to be 18 or older to create an account.
    type: individual
  minimum_age:
    text: You need to be 18 or older to create an account.
    value: '18'
  restricted_uses:
  - summary: Bots and scripts
    text: Don't use bots or scripts to post, react, confirm codes or enter draws.
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
name: CartRevolt
provenance_date: '2026-11-09'
provider_name: CartRevolt
provider_slug: cartrevolt-com
slug: cartrevolt-com-eligibility
source_date: '2026-11-09'
source_filename: cartrevolt-com-eligibility.yml
source_heading: Eligibility
source_page: https://cartrevolt.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CartRevolt\naid: cartrevolt-com\nurl: https://cartrevolt.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: CartRevolt is run for people in the United States.\nentity_types:\n- type: individual\n  text: You need to be 18 or older to create an account.\nrestricted_uses:\n- summary: Bots and scripts\n  text: Don't use bots or scripts to post, react, confirm codes or enter draws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You need to be 18 or older to create an account.\n"
source_yaml_url: https://artifacts.apis.io/cartrevolt-com/eligibility/cartrevolt-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CartRevolt's own page on 2026-11-09.
synthetic: false
tags:
- Coupons
- Discounts
- Gift Cards
- Shopping Hacks
- Community Deals
---
