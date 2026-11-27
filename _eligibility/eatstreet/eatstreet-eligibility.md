---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: EatStreet is intended for users who are 18 years of age or older.
    type: individual
  - text: If you are using the Sites or Services on behalf of an entity, organization, or company, you represent and warrant that you have the authority to bind that organization to this Agreement
    type: business
  minimum_age:
    text: EatStreet is intended for users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Alcohol orders
    text: You agree that you will only order alcohol products if you are 21 years of age or older.
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
name: EatStreet
provenance_date: '2026-11-09'
provider_name: EatStreet
provider_slug: eatstreet
slug: eatstreet-eligibility
source_date: '2026-11-09'
source_filename: eatstreet-eligibility.yml
source_heading: Eligibility
source_page: https://eatstreet.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EatStreet\naid: eatstreet\nurl: https://eatstreet.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: EatStreet is intended for users who are 18 years of age or older.\n- type: business\n  text: If you are using the Sites or Services on behalf of an entity, organization, or company, you represent and\n    warrant that you have the authority to bind that organization to this Agreement\nrestricted_uses:\n- summary: Alcohol orders\n  text: You agree that you will only order alcohol products if you are 21 years of age or older.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: EatStreet is intended for users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/eatstreet/eligibility/eatstreet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from EatStreet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Delivery
- Restaurant
- Online Ordering
- Marketplace
- Local Commerce
- Consumer
- Point-of-Sale
- OAuth
- Authentication
---
