---
api_specs:
- filename: upgrade-marketing-offers-api-openapi.yml
  format: yaml
  label: Upgrade Marketing Offers API
  slug: upgrade-marketing-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upgrade/openapi/upgrade-marketing-offers-api-openapi.yml
- filename: upgrade-orders-api-openapi.yml
  format: yaml
  label: Upgrade Orders API
  slug: upgrade-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upgrade/openapi/upgrade-orders-api-openapi.yml
- filename: upgrade-transactions-api-openapi.yml
  format: yaml
  label: Upgrade Transactions API
  slug: upgrade-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/upgrade/openapi/upgrade-transactions-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This Site is intended for individuals who are residents of the United States and at least eighteen (18) years of age
  entity_types:
  - text: This Site is intended for individuals who are residents of the United States and at least eighteen (18) years of age
    type: individual
  minimum_age:
    text: at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Loan proceeds limited to merchant purchases
    text: You agree that all loan proceeds will be used to fund the purchase of services from the designated merchant. You will not use the Services to accomplish a cash advance, wire or money transfer.
  - summary: Prohibited purchase categories
    text: Ammunition, firearms, certain firearm parts or accessories, and certain weapons or knives regulated under applicable law; Narcotics, steroids, controlled substances, quasi-pharmaceuticals, or drug paraphernalia; Currency in any form, including virtual and digital currency; Gift cards or gift certificates
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
name: Upgrade
provenance_date: '2026-11-10'
provider_name: Upgrade
provider_slug: upgrade
slug: upgrade-eligibility
source_date: '2026-11-10'
source_filename: upgrade-eligibility.yml
source_heading: Eligibility
source_page: https://www.upgrade.com/funnel/borrower-documents/TERMS_OF_USE
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Upgrade\naid: upgrade\nurl: https://www.upgrade.com/funnel/borrower-documents/TERMS_OF_USE\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This Site is intended for individuals who are residents of the United States and at least eighteen (18)\n    years of age\nentity_types:\n- type: individual\n  text: This Site is intended for individuals who are residents of the United States and at least eighteen (18)\n    years of age\nrestricted_uses:\n- summary: Loan proceeds limited to merchant purchases\n  text: You agree that all loan proceeds will be used to fund the purchase of services\
  \ from the designated merchant.\n    You will not use the Services to accomplish a cash advance, wire or money transfer.\n- summary: Prohibited purchase categories\n  text: Ammunition, firearms, certain firearm parts or accessories, and certain weapons or knives regulated under\n    applicable law; Narcotics, steroids, controlled substances, quasi-pharmaceuticals, or drug paraphernalia; Currency\n    in any form, including virtual and digital currency; Gift cards or gift certificates\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/upgrade/eligibility/upgrade-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Upgrade's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Buy Now Pay Later
- Payments
- Credit Cards
- Banking
- Travel
---
