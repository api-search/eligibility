---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Delivery to Calgary, Airdrie, Chestermere, and Cochrane
  entity_types:
  - text: You must be 18 years or older to create an account
    type: individual
  - text: vendors (store owners), vendor staff (managers/cashiers), suppliers, and drivers
    type: business
  minimum_age:
    text: You must be 18 years or older to create an account
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Suppliers must be approved by BuyNearby before listing products or receiving purchase orders
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BuyNearby
provenance_date: '2026-11-09'
provider_name: BuyNearby
provider_slug: buynearby-store
slug: buynearby-store-eligibility
source_date: '2026-11-09'
source_filename: buynearby-store-eligibility.yml
source_heading: Eligibility
source_page: https://buynearby.store/terms-of-service.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BuyNearby\naid: buynearby-store\nurl: https://buynearby.store/terms-of-service.php\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Delivery to Calgary, Airdrie, Chestermere, and Cochrane\nentity_types:\n- type: individual\n  text: You must be 18 years or older to create an account\n- type: business\n  text: vendors (store owners), vendor staff (managers/cashiers), suppliers, and drivers\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Suppliers must be approved by BuyNearby before listing products or receiving purchase orders\nminimum_age:\n\
  \  value: '18'\n  text: You must be 18 years or older to create an account\n"
source_yaml_url: https://artifacts.apis.io/buynearby-store/eligibility/buynearby-store-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 5 quoted statements, read from BuyNearby's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Delivery
- Grocery
- Calgary
- Marketplace
- Local Business
---
