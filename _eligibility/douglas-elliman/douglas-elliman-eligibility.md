---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The market area served by the Site includes New York City, Long Island, Westchester and Hudson County, New Jersey.
  entity_types:
  - text: You must be eighteen (18) years of age or older to register for an Account.
    type: individual
  minimum_age:
    text: You must be eighteen (18) years of age or older to register for an Account.
    value: '18'
  restricted_uses:
  - summary: Non-commercial, bona fide real estate interest
    text: You represent that you are a prospective purchaser, seller, lessee or lessor of real property in the geographic areas where Douglas Elliman is licensed and operating with a bona fide interest in the purchase, sale or lease of such real property.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must complete the Site registration process to create an account with a user name and password
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Douglas Elliman
provenance_date: '2026-11-09'
provider_name: Douglas Elliman
provider_slug: douglas-elliman
slug: douglas-elliman-eligibility
source_date: '2026-11-09'
source_filename: douglas-elliman-eligibility.yml
source_heading: Eligibility
source_page: https://www.elliman.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Douglas Elliman\naid: douglas-elliman\nurl: https://www.elliman.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The market area served by the Site includes New York City, Long Island, Westchester and Hudson County, New\n    Jersey.\nentity_types:\n- type: individual\n  text: You must be eighteen (18) years of age or older to register for an Account.\nrestricted_uses:\n- summary: Non-commercial, bona fide real estate interest\n  text: You represent that you are a prospective purchaser, seller, lessee or lessor of real property in the geographic\n    areas\
  \ where Douglas Elliman is licensed and operating with a bona fide interest in the purchase, sale or lease\n    of such real property.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must complete the Site registration process to create an account with a user name and password\nminimum_age:\n  value: '18'\n  text: You must be eighteen (18) years of age or older to register for an Account.\n"
source_yaml_url: https://artifacts.apis.io/douglas-elliman/eligibility/douglas-elliman-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Douglas Elliman's own page on 2026-11-09.
synthetic: false
tags:
- Real Estate
- United States
- Brokerage
- Property Listings
- MLS
- IDX
- RESO
- Rentals
- Commercial Real Estate
- Property Management
- Title
- Escrow
- PropTech
- Luxury Real Estate
- New Development
---
