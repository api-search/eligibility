---
api_specs:
- filename: best-buy-products-api-openapi.yml
  format: yaml
  label: Best Buy Products API
  slug: best-buy-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-buy/openapi/best-buy-products-api-openapi.yml
- filename: best-buy-recommendations-api-openapi.yml
  format: yaml
  label: Best Buy Recommendations API
  slug: best-buy-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-buy/openapi/best-buy-recommendations-api-openapi.yml
- filename: best-buy-stores-api-openapi.yml
  format: yaml
  label: Best Buy Stores API
  slug: best-buy-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-buy/openapi/best-buy-stores-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commerce and checkout requirements
    text: Use of the Commerce Gateway API requires our pre-approval and may not be available to everyone.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Use of the Commerce Gateway API requires our pre-approval and may not be available to everyone.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Best Buy
provenance_date: '2026-11-09'
provider_name: Best Buy
provider_slug: best-buy
slug: best-buy-eligibility
source_date: '2026-11-09'
source_filename: best-buy-eligibility.yml
source_heading: Eligibility
source_page: https://developer.bestbuy.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Best Buy\naid: best-buy\nurl: https://developer.bestbuy.com/legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commerce and checkout requirements\n  text: Use of the Commerce Gateway API requires our pre-approval and may not be available to everyone.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Use of the Commerce Gateway API requires our pre-approval and may not be available to everyone.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/best-buy/eligibility/best-buy-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Best Buy's own page on 2026-11-09.
synthetic: false
tags:
- Fortune 100
- Retail
- Consumer Electronics
- E-Commerce
- Product
- Stores
---
