---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Members must be consumers within the meaning of section 13 of the German Civil Code (BGB), i.e. persons who do not enter into a legal transaction primarily for commercial or self-employed purposes.
    type: individual
  minimum_age:
    text: Persons (i) under the age of 18 (ii) with limited or no legal capacity are not permitted to set up a Member account.
    value: '18'
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
name: NeoTaste
provenance_date: '2026-11-10'
provider_name: NeoTaste
provider_slug: neotaste
slug: neotaste-eligibility
source_date: '2026-11-10'
source_filename: neotaste-eligibility.yml
source_heading: Eligibility
source_page: https://neotaste.com/de/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NeoTaste\naid: neotaste\nurl: https://neotaste.com/de/en/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Members must be consumers within the meaning of section 13 of the German Civil Code (BGB), i.e. persons\n    who do not enter into a legal transaction primarily for commercial or self-employed purposes.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Persons (i) under the age of 18 (ii) with limited or no legal capacity\
  \ are not permitted to set up a Member\n    account.\n"
source_yaml_url: https://artifacts.apis.io/neotaste/eligibility/neotaste-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from NeoTaste's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Restaurant
- Dining
- Food and Beverage
- Deals
- Discounts
- Consumer App
- Discovery
- Loyalty
- Local
---
