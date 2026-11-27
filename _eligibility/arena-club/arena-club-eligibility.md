---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years of age, or the legal age of majority in your state of residence, if higher, to create an Account or use the Service.
    type: individual
  - text: You represent that you have the authority to bind yourself to this Agreement.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age, or the legal age of majority in your state of residence, if higher, to create an Account or use the Service.
    value: '18'
  restricted_uses:
  - summary: Alcoholic beverage purchases require age 21
    text: You must be at least twenty-one (21) years of age to purchase Alcoholic Beverage Digital Reveals, participate in the free-to-enter ArenaClub.com sweepstakes promotion in connection with Alcoholic Beverage Digital Reveals, accept or redeem an Alcoholic Beverage Offer, or purchase, receive, or take delivery of any product containing alcohol.
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
name: Arena Club
provenance_date: '2026-11-09'
provider_name: Arena Club
provider_slug: arena-club
slug: arena-club-eligibility
source_date: '2026-11-09'
source_filename: arena-club-eligibility.yml
source_heading: Eligibility
source_page: https://info.arenaclub.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arena Club\naid: arena-club\nurl: https://info.arenaclub.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age, or the legal age of majority in your state of residence,\n    if higher, to create an Account or use the Service.\n- type: business\n  text: You represent that you have the authority to bind yourself to this Agreement.\nrestricted_uses:\n- summary: Alcoholic beverage purchases require age 21\n  text: You must be at least twenty-one (21) years of age to purchase\
  \ Alcoholic Beverage Digital Reveals, participate\n    in the free-to-enter ArenaClub.com sweepstakes promotion in connection with Alcoholic Beverage Digital Reveals,\n    accept or redeem an Alcoholic Beverage Offer, or purchase, receive, or take delivery of any product containing\n    alcohol.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age, or the legal age of majority in your state of residence,\n    if higher, to create an Account or use the Service.\n"
source_yaml_url: https://artifacts.apis.io/arena-club/eligibility/arena-club-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Arena Club's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Collectibles
- Trading Cards
- Marketplace
- E-Commerce
- Sports
- Grading
- Consumer
---
