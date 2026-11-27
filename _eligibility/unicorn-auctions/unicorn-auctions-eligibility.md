---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Service may not be legal by certain persons or in certain countries.
  minimum_age:
    text: The Service is offered and available to users who are 21 years of age or older.
    value: '21'
  restricted_uses:
  - summary: Alcohol law circumvention
    text: For the purposes of circumventing or willfully and intentionally violating federal, state or local alcohol beverage laws and regulations.
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
name: Unicorn Auctions
provenance_date: '2026-11-10'
provider_name: Unicorn Auctions
provider_slug: unicorn-auctions
slug: unicorn-auctions-eligibility
source_date: '2026-11-10'
source_filename: unicorn-auctions-eligibility.yml
source_heading: Eligibility
source_page: https://www.unicornauctions.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unicorn Auctions\naid: unicorn-auctions\nurl: https://www.unicornauctions.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Service may not be legal by certain persons or in certain countries.\nentity_types: []\nrestricted_uses:\n- summary: Alcohol law circumvention\n  text: For the purposes of circumventing or willfully and intentionally violating federal, state or local alcohol\n    beverage laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '21'\n  text: The Service is offered\
  \ and available to users who are 21 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/unicorn-auctions/eligibility/unicorn-auctions-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Unicorn Auctions's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Auctions
- Marketplace
- E-Commerce
- Collectibles
- Wine
- Spirits
- Retail
- Consumer
---
