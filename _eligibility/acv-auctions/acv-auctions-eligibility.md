---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer may only register for and receive the Services if Customer is legally eligible to purchase or sell wholesale vehicles for resale.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Resale purpose only
    text: The vehicle is purchased solely for resale in the form of tangible personal property in the regular course of business
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Upon receipt and approval of Customer’s registration documents, Customer and Customer’s designated authorized representatives (“Authorized Representatives”) will be issued unique names and passwords to access the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ACV Auctions
provenance_date: '2026-11-09'
provider_name: ACV Auctions
provider_slug: acv-auctions
slug: acv-auctions-eligibility
source_date: '2026-11-09'
source_filename: acv-auctions-eligibility.yml
source_heading: Eligibility
source_page: https://www.acvauctions.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ACV Auctions\naid: acv-auctions\nurl: https://www.acvauctions.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer may only register for and receive the Services if Customer is legally eligible to purchase or sell\n    wholesale vehicles for resale.\nrestricted_uses:\n- summary: Resale purpose only\n  text: The vehicle is purchased solely for resale in the form of tangible personal property in the regular course\n    of business\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text:\
  \ Upon receipt and approval of Customer’s registration documents, Customer and Customer’s designated authorized\n    representatives (“Authorized Representatives”) will be issued unique names and passwords to access the Services\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/acv-auctions/eligibility/acv-auctions-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from ACV Auctions's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Vertical Software
- Automotive
- Marketplace
- Auctions
- Used Vehicles
- Wholesale
- Dealer Services
---
