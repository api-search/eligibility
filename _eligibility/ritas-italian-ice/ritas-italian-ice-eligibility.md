---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Loyalty Program is intended for personal use only.
    type: individual
  minimum_age:
    text: The Loyalty Program is not targeted towards, nor intended for use by, anyone under the age of 13.
    value: '13'
  restricted_uses:
  - summary: Commercial use prohibited
    text: Commercial use is prohibited.
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
name: Rita's Italian Ice
provenance_date: '2026-11-10'
provider_name: Rita's Italian Ice
provider_slug: ritas-italian-ice
slug: ritas-italian-ice-eligibility
source_date: '2026-11-10'
source_filename: ritas-italian-ice-eligibility.yml
source_heading: Eligibility
source_page: https://www.ritasice.com/loyalty-terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rita's Italian Ice\naid: ritas-italian-ice\nurl: https://www.ritasice.com/loyalty-terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Loyalty Program is intended for personal use only.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: Commercial use is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Loyalty Program is not targeted towards, nor intended for use by, anyone under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/ritas-italian-ice/eligibility/ritas-italian-ice-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Rita's Italian Ice's own page on 2026-11-10.
synthetic: false
tags:
- Restaurant
- Food and Beverage
- Frozen Desserts
- Franchise
- Quick Service Restaurant
---
