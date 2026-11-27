---
api_specs:
- filename: shopback-account-linking-api-openapi.yml
  format: yaml
  label: ShopBack Account Linking API
  slug: shopback-account-linking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-account-linking-api-openapi.yml
- filename: shopback-authentication-api-openapi.yml
  format: yaml
  label: ShopBack Authentication API
  slug: shopback-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-authentication-api-openapi.yml
- filename: shopback-notification-api-openapi.yml
  format: yaml
  label: ShopBack Notification API
  slug: shopback-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-notification-api-openapi.yml
- filename: shopback-orders-api-openapi.yml
  format: yaml
  label: ShopBack Orders API
  slug: shopback-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-orders-api-openapi.yml
- filename: shopback-pre-auth-api-openapi.yml
  format: yaml
  label: ShopBack Pre Auth API
  slug: shopback-pre-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/shopback/openapi/shopback-pre-auth-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Cashback Program is not available to and should not be accessed or used by residents outside of the 50 United States or Washington D.C.
  entity_types:
  - text: This Agreement constitutes a legally binding agreement between each individual who accesses or uses the ShopBack Platforms or the Services or who maintains a ShopBack Account
    type: individual
  minimum_age:
    text: To create a ShopBack account, you must be at least 18 years old.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may create a ShopBack Account free of charge by providing the relevant details that ShopBack may request from time to time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ShopBack
provenance_date: '2026-11-10'
provider_name: ShopBack
provider_slug: shopback
slug: shopback-eligibility
source_date: '2026-11-10'
source_filename: shopback-eligibility.yml
source_heading: Eligibility
source_page: https://support.shopback.com/hc/en-us/articles/33321351340307-Terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShopBack\naid: shopback\nurl: https://support.shopback.com/hc/en-us/articles/33321351340307-Terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Cashback Program is not available to and should not be accessed or used by residents outside of the\n    50 United States or Washington D.C.\nentity_types:\n- type: individual\n  text: This Agreement constitutes a legally binding agreement between each individual who accesses or uses the\n    ShopBack Platforms or the Services or who maintains a ShopBack Account\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: You may create a ShopBack Account free of charge by providing the relevant details that ShopBack may request\n    from time to time.\nminimum_age:\n  value: '18'\n  text: To create a ShopBack account, you must be at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/shopback/eligibility/shopback-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from ShopBack's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Cashback
- Rewards
- Loyalty
- E-Commerce
- Buy Now Pay Later
- Point-of-Sale
- Checkout
- Singapore
---
