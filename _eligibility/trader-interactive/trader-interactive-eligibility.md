---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: In order to purchase products or services from this Website or to use this Website to sell a product or service, you must be at least eighteen (18) years of age and use a credit card.
    type: individual
  minimum_age:
    text: you must be at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Non-commercial use only
    text: You may use the content, information, consumer reviews, data and materials from, and the products and services available through, this Website solely for your personal and non-commercial use.
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
name: Trader Interactive
provenance_date: '2026-11-10'
provider_name: Trader Interactive
provider_slug: trader-interactive
slug: trader-interactive-eligibility
source_date: '2026-11-10'
source_filename: trader-interactive-eligibility.yml
source_heading: Eligibility
source_page: https://www.traderinteractive.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trader Interactive\naid: trader-interactive\nurl: https://www.traderinteractive.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: In order to purchase products or services from this Website or to use this Website to sell a product or\n    service, you must be at least eighteen (18) years of age and use a credit card.\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You may use the content, information, consumer reviews, data and materials from, and the products and services\n    available through, this Website\
  \ solely for your personal and non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/trader-interactive/eligibility/trader-interactive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Trader Interactive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Classifieds
- Automotive
- Power-Sports
- Recreational Vehicles
- Commercial Trucks
- Heavy Equipment
- Dealer Services
- Digital Advertising
- Vehicle Listings
- Media
---
