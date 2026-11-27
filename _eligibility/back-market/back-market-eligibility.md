---
api_specs:
- filename: back-market-backbox-api-openapi.yml
  format: yaml
  label: Back Market Backbox API
  slug: back-market-backbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-backbox-api-openapi.yml
- filename: back-market-backship-api-openapi.yml
  format: yaml
  label: Back Market Backship API
  slug: back-market-backship-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-backship-api-openapi.yml
- filename: back-market-care-api-openapi.yml
  format: yaml
  label: Back Market Care API
  slug: back-market-care-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-care-api-openapi.yml
- filename: back-market-categories-api-openapi.yml
  format: yaml
  label: Back Market Categories API
  slug: back-market-categories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-categories-api-openapi.yml
- filename: back-market-listings-api-openapi.yml
  format: yaml
  label: Back Market Listings API
  slug: back-market-listings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-listings-api-openapi.yml
- filename: back-market-orderline-api-openapi.yml
  format: yaml
  label: Back Market Orderline API
  slug: back-market-orderline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-orderline-api-openapi.yml
- filename: back-market-orders-api-openapi.yml
  format: yaml
  label: Back Market Orders API
  slug: back-market-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-orders-api-openapi.yml
- filename: back-market-buy-back-api-openapi.yml
  format: yaml
  label: Back Market Buy Back API
  slug: back-market-buy-back-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-buy-back-api-openapi.yml
- filename: back-market-task-manager-api-openapi.yml
  format: yaml
  label: Back Market task manager API
  slug: back-market-task-manager-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/back-market/openapi/back-market-task-manager-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Product(s) presented for sale on the Platform can only be shipped to the 48 contiguous states of the United States.
  entity_types:
  - text: Natural person(s) must be 16 years old or older to be able to purchase Product(s) on the Platform
    type: individual
  - text: Seller means any professional seller of Products registered on the Platform.
    type: business
  minimum_age:
    text: Natural person(s) must be 16 years old or older to be able to purchase Product(s) on the Platform and have the capacity to take legal actions or have the authority of their parent or legal guardian to transact if they are under 18 years old.
    value: '16'
  restricted_uses:
  - summary: Export control and prohibited US purposes
    text: The User will not use the Platform for any purpose prohibited by U.S. law, including the development, design, manufacture or production of missiles, or nuclear, chemical or biological weapons.
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
name: Back Market
provenance_date: '2026-11-09'
provider_name: Back Market
provider_slug: back-market
slug: back-market-eligibility
source_date: '2026-11-09'
source_filename: back-market-eligibility.yml
source_heading: Eligibility
source_page: https://www.backmarket.com/en-us/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Back Market\naid: back-market\nurl: https://www.backmarket.com/en-us/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Product(s) presented for sale on the Platform can only be shipped to the 48 contiguous states of the United\n    States.\nentity_types:\n- type: individual\n  text: Natural person(s) must be 16 years old or older to be able to purchase Product(s) on the Platform\n- type: business\n  text: Seller means any professional seller of Products registered on the Platform.\nrestricted_uses:\n- summary: Export control and prohibited US purposes\n\
  \  text: The User will not use the Platform for any purpose prohibited by U.S. law, including the development, design,\n    manufacture or production of missiles, or nuclear, chemical or biological weapons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Natural person(s) must be 16 years old or older to be able to purchase Product(s) on the Platform and have\n    the capacity to take legal actions or have the authority of their parent or legal guardian to transact if they\n    are under 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/back-market/eligibility/back-market-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Back Market's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Marketplace
- Retail
- Refurbished Electronics
- Circular Economy
- Order
- Listings
- Product Catalog
- Logistics
- Customer Service
---
