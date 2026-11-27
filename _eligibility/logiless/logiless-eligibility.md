---
api_specs:
- filename: logiless-articles-api-openapi.yml
  format: yaml
  label: Logiless Articles API
  slug: logiless-articles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-articles-api-openapi.yml
- filename: logiless-inbound-deliveries-api-openapi.yml
  format: yaml
  label: Logiless Inbound Deliveries API
  slug: logiless-inbound-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-inbound-deliveries-api-openapi.yml
- filename: logiless-inter-warehouse-transfers-api-openapi.yml
  format: yaml
  label: Logiless Inter-Warehouse Transfers API
  slug: logiless-inter-warehouse-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-inter-warehouse-transfers-api-openapi.yml
- filename: logiless-inventory-api-openapi.yml
  format: yaml
  label: Logiless Inventory API
  slug: logiless-inventory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-inventory-api-openapi.yml
- filename: logiless-locations-api-openapi.yml
  format: yaml
  label: Logiless Locations API
  slug: logiless-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-locations-api-openapi.yml
- filename: logiless-outbound-deliveries-api-openapi.yml
  format: yaml
  label: Logiless Outbound Deliveries API
  slug: logiless-outbound-deliveries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-outbound-deliveries-api-openapi.yml
- filename: logiless-sales-orders-api-openapi.yml
  format: yaml
  label: Logiless Sales Orders API
  slug: logiless-sales-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-sales-orders-api-openapi.yml
- filename: logiless-sales-returns-api-openapi.yml
  format: yaml
  label: Logiless Sales Returns API
  slug: logiless-sales-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-sales-returns-api-openapi.yml
- filename: logiless-suppliers-api-openapi.yml
  format: yaml
  label: Logiless Suppliers API
  slug: logiless-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/logiless/openapi/logiless-suppliers-api-openapi.yml
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
  - summary: Purpose limitation
    text: 前項の利用申込みが、当社API利用目的に該当しないもしくは反するものであると当社が判断した場合
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 当社が当該利用申込みを承諾する旨を通知した時点で、API利用者と当社との間で当社APIの利用契約が成立したものとみなされます。
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Logiless
provenance_date: '2026-11-09'
provider_name: Logiless
provider_slug: logiless
slug: logiless-eligibility
source_date: '2026-11-09'
source_filename: logiless-eligibility.yml
source_heading: Eligibility
source_page: https://www.logiless.com/legal/terms-for-api/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Logiless\naid: logiless\nurl: https://www.logiless.com/legal/terms-for-api/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Purpose limitation\n  text: 前項の利用申込みが、当社API利用目的に該当しないもしくは反するものであると当社が判断した場合\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 当社が当該利用申込みを承諾する旨を通知した時点で、API利用者と当社との間で当社APIの利用契約が成立したものとみなされます。\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/logiless/eligibility/logiless-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Logiless's own page on 2026-11-09.
synthetic: false
tags:
- Logistics
- E-Commerce
- Order Management
- Warehouse Management
- Inventory
- Fulfillment
- Shipping
- OMS
- WMS
- Japan
---
