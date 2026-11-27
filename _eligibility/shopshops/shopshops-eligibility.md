---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You represent that you are not located in a country that is subject to a U.S. Government embargo, or that has been designated by the U.S. Government as a “terrorist supporting” country
  entity_types:
  - text: 'By creating an Account and using the Application, you agree: (a) you are at least eighteen (18) years of age'
    type: individual
  - text: References in this Agreement to “you” or “your” refer to both you and any organization on whose behalf you act.
    type: business
  minimum_age:
    text: (a) you are at least eighteen (18) years of age
    value: '18'
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
name: ShopShops
provenance_date: '2026-11-10'
provider_name: ShopShops
provider_slug: shopshops
slug: shopshops-eligibility
source_date: '2026-11-10'
source_filename: shopshops-eligibility.yml
source_heading: Eligibility
source_page: https://www.shopshopslive.com/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShopShops\naid: shopshops\nurl: https://www.shopshopslive.com/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You represent that you are not located in a country that is subject to a U.S. Government embargo, or that\n    has been designated by the U.S. Government as a “terrorist supporting” country\nentity_types:\n- type: individual\n  text: 'By creating an Account and using the Application, you agree: (a) you are at least eighteen (18) years of\n    age'\n- type: business\n  text: References in this Agreement to “you” or “your” refer to both you and any\
  \ organization on whose behalf you\n    act.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: (a) you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/shopshops/eligibility/shopshops-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from ShopShops's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Commerce
- E-Commerce
- Marketplace
- Live Shopping
- Luxury Resale
- Agentic Commerce
- Shopify
---
