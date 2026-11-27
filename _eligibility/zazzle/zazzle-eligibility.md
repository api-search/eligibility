---
api_specs:
- filename: zazzle-create-a-product-api-openapi.yml
  format: yaml
  label: Zazzle Create a Product API
  slug: zazzle-create-a-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zazzle/openapi/zazzle-create-a-product-api-openapi.yml
- filename: zazzle-realview-api-openapi.yml
  format: yaml
  label: Zazzle Real View API
  slug: zazzle-realview-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zazzle/openapi/zazzle-realview-api-openapi.yml
- filename: zazzle-vendor-api-openapi.yml
  format: yaml
  label: Zazzle Vendor API
  slug: zazzle-vendor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zazzle/openapi/zazzle-vendor-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Certain Zazzle Products may only be shipped and/or distributed to limited geographic regions/countries.
  minimum_age:
    text: You must be at least eighteen (18) years of age to use this Site.
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
name: Zazzle
provenance_date: '2026-11-10'
provider_name: Zazzle
provider_slug: zazzle
slug: zazzle-eligibility
source_date: '2026-11-10'
source_filename: zazzle-eligibility.yml
source_heading: Eligibility
source_page: https://www.zazzle.com/terms/user_agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zazzle\naid: zazzle\nurl: https://www.zazzle.com/terms/user_agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Certain Zazzle Products may only be shipped and/or distributed to limited geographic regions/countries.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age to use this Site.\n"
source_yaml_url: https://artifacts.apis.io/zazzle/eligibility/zazzle-eligibility.yml
stated_fields:
- countries
- minimum_age
summary_line: 2 quoted statements, read from Zazzle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Marketplace
- Print on Demand
- Manufacturing
- Retail
- Affiliates
- Custom Products
- Order Management
- Shipping
---
