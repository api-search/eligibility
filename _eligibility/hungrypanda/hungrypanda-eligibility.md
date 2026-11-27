---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Select country United Kingdom
  entity_types:
  - text: You need to set up a HungryPanda account to use our Platform for placing Orders.
    type: individual
  minimum_age:
    text: You warrant that you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Age-restricted products
    text: If you place an Order which includes alcohol beverages, cigarettes, or other age-restricted products, you must present a government-issued identification card as proof of age upon request
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
name: HungryPanda
provenance_date: '2026-11-09'
provider_name: HungryPanda
provider_slug: hungrypanda
slug: hungrypanda-eligibility
source_date: '2026-11-09'
source_filename: hungrypanda-eligibility.yml
source_heading: Eligibility
source_page: https://fast-leaflet-uk.hungrypanda.co/articleRule?appTypeId=1
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HungryPanda\naid: hungrypanda\nurl: https://fast-leaflet-uk.hungrypanda.co/articleRule?appTypeId=1\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Select country United Kingdom\nentity_types:\n- type: individual\n  text: You need to set up a HungryPanda account to use our Platform for placing Orders.\nrestricted_uses:\n- summary: Age-restricted products\n  text: If you place an Order which includes alcohol beverages, cigarettes, or other age-restricted products, you\n    must present a government-issued identification card as proof of age upon request\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You warrant that you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/hungrypanda/eligibility/hungrypanda-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from HungryPanda's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Food Delivery
- Delivery
- Marketplace
- Restaurant
- Grocery
- Logistics
- E-Commerce
- Merchants
- Point-of-Sale
---
