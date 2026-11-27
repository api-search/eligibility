---
api_specs:
- filename: tindie-order-api-openapi.yml
  format: yaml
  label: Tindie Order API
  slug: tindie-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tindie/openapi/tindie-order-api-openapi.yml
- filename: tindie-orderitem-api-openapi.yml
  format: yaml
  label: Tindie Orderitem API
  slug: tindie-orderitem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tindie/openapi/tindie-orderitem-api-openapi.yml
- filename: tindie-product-api-openapi.yml
  format: yaml
  label: Tindie Product API
  slug: tindie-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tindie/openapi/tindie-product-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users must use Tindie only from locations where the service, checkout, and payout methods are permitted.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted products
    text: Tindie may prohibit products that are illegal, unsafe, counterfeit, infringing, deceptive, regulated, sanctioned, or inconsistent with the marketplace's purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require identity, business, tax, banking, product, transaction, or other verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tindie
provenance_date: '2026-11-10'
provider_name: Tindie
provider_slug: tindie
slug: tindie-eligibility
source_date: '2026-11-10'
source_filename: tindie-eligibility.yml
source_heading: Eligibility
source_page: https://www.tindie.com/about/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tindie\naid: tindie\nurl: https://www.tindie.com/about/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users must use Tindie only from locations where the service, checkout, and payout methods are permitted.\nentity_types: []\nrestricted_uses:\n- summary: Restricted products\n  text: Tindie may prohibit products that are illegal, unsafe, counterfeit, infringing, deceptive, regulated, sanctioned,\n    or inconsistent with the marketplace's purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require identity, business, tax, banking, product,\
  \ transaction, or other verification.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tindie/eligibility/tindie-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Tindie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Hardware
- Electronics
- Maker
- E-Commerce
- Open Source Hardware
- Order
---
