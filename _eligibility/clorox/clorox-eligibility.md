---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: products sold on the eCommerce Sites are intended for end use in the United States and are not labeled or intended for international distribution.
  entity_types:
  - text: Unless otherwise indicated, you only may use our Sites and our Content for your personal use as an individual.
    type: individual
  minimum_age:
    text: YOU MUST BE AT LEAST 13 TO ACCESS AND USE OUR SITES.
    value: '13'
  restricted_uses:
  - summary: Promo codes limited to consumers
    text: Only consumers can use promo codes, they cannot be used be resellers, wholesalers, practitioners, or the like.
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
name: The Clorox Company
provenance_date: '2026-11-09'
provider_name: The Clorox Company
provider_slug: clorox
slug: clorox-eligibility
source_date: '2026-11-09'
source_filename: clorox-eligibility.yml
source_heading: Eligibility
source_page: https://www.thecloroxcompany.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Clorox Company\naid: clorox\nurl: https://www.thecloroxcompany.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: products sold on the eCommerce Sites are intended for end use in the United States and are not labeled or\n    intended for international distribution.\nentity_types:\n- type: individual\n  text: Unless otherwise indicated, you only may use our Sites and our Content for your personal use as an individual.\nrestricted_uses:\n- summary: Promo codes limited to consumers\n  text: Only consumers can use promo codes, they cannot be used be resellers,\
  \ wholesalers, practitioners, or the\n    like.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: YOU MUST BE AT LEAST 13 TO ACCESS AND USE OUR SITES.\n"
source_yaml_url: https://artifacts.apis.io/clorox/eligibility/clorox-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from The Clorox Company's own page on 2026-11-09.
synthetic: false
tags:
- Cleaning Products
- Consumer Goods
- Consumer Packaged Goods
- Disinfectants
- Household Products
- Manufacturer
- Fortune 500
- Safety Data Sheets
- Product Transparency
- MuleSoft
---
