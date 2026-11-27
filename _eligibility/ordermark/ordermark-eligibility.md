---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may only use this Website if you are at least 13 years of age.
    type: individual
  - text: IF YOU ARE ACCESSING THE SITE AND SERVICES ON BEHALF OF A COMPANY THAT YOU REPRESENT (“YOUR COMPANY”), THEN YOU AGREE TO BIND BOTH YOURSELF AS AN INDIVIDUAL, AND YOUR COMPANY, TO ALL OF THE TERMS OF THIS AGREEMENT.
    type: business
  minimum_age:
    text: You may only use this Website if you are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: Prohibited activities
    text: You may not access or use the Site for any purpose other than that for which we make the Site available.
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
name: Ordermark
provenance_date: '2026-11-10'
provider_name: Ordermark
provider_slug: ordermark
slug: ordermark-eligibility
source_date: '2026-11-10'
source_filename: ordermark-eligibility.yml
source_heading: Eligibility
source_page: https://www.ordermark.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ordermark\naid: ordermark\nurl: https://www.ordermark.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may only use this Website if you are at least 13 years of age.\n- type: business\n  text: IF YOU ARE ACCESSING THE SITE AND SERVICES ON BEHALF OF A COMPANY THAT YOU REPRESENT (“YOUR COMPANY”), THEN\n    YOU AGREE TO BIND BOTH YOURSELF AS AN INDIVIDUAL, AND YOUR COMPANY, TO ALL OF THE TERMS OF THIS AGREEMENT.\nrestricted_uses:\n- summary: Prohibited activities\n  text: You may not access or use the Site for any purpose\
  \ other than that for which we make the Site available.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may only use this Website if you are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/ordermark/eligibility/ordermark-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Ordermark's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Restaurant Technology
- Food Delivery
- Order Management
- Order Aggregation
- POS Integration
- Restaurant
---
