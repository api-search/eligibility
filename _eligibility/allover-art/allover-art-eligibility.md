---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We ship worldwide where we have operational delivery.
  entity_types:
  - text: You must be at least 18 years old (or the age of majority in your jurisdiction) to open an account and place orders.
    type: individual
  - text: Buyers who are legal entities
    type: business
  minimum_age:
    text: You must be at least 18 years old (or the age of majority in your jurisdiction) to open an account and place orders.
    value: '18'
  restricted_uses:
  - summary: Unlawful use or fraud
    text: Use the service for unlawful purposes or in violation of any applicable law.
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
name: All-Over Print Tees
provenance_date: '2026-11-09'
provider_name: All-Over Print Tees
provider_slug: allover-art
slug: allover-art-eligibility
source_date: '2026-11-09'
source_filename: allover-art-eligibility.yml
source_heading: Eligibility
source_page: https://allover.art/info/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: All-Over Print Tees\naid: allover-art\nurl: https://allover.art/info/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We ship worldwide where we have operational delivery.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to open an account and place\n    orders.\n- type: business\n  text: Buyers who are legal entities\nrestricted_uses:\n- summary: Unlawful use or fraud\n  text: Use the service for unlawful purposes or in violation of any applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority in your jurisdiction) to open an account and place\n    orders.\n"
source_yaml_url: https://artifacts.apis.io/allover-art/eligibility/allover-art-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from All-Over Print Tees's own page on 2026-11-09.
synthetic: false
tags:
- Print on Demand
- Graphic Tees
- Worldwide Shipping
---
