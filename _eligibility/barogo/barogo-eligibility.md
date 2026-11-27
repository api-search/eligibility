---
api_specs:
- filename: barogo-areas-api-openapi.yml
  format: yaml
  label: Barogo Areas API
  slug: barogo-areas-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-areas-api-openapi.yml
- filename: barogo-delivery-api-openapi.yml
  format: yaml
  label: Barogo Delivery API
  slug: barogo-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-delivery-api-openapi.yml
- filename: barogo-deposits-api-openapi.yml
  format: yaml
  label: Barogo Deposits API
  slug: barogo-deposits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-deposits-api-openapi.yml
- filename: barogo-orders-api-openapi.yml
  format: yaml
  label: Barogo Orders API
  slug: barogo-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-orders-api-openapi.yml
- filename: barogo-stores-api-openapi.yml
  format: yaml
  label: Barogo Stores API
  slug: barogo-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/barogo/openapi/barogo-stores-api-openapi.yml
claim_count: 3
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
  - summary: Items over 3 million won
    text: ⑤ 배송물의 가액이 300만원을 초과하는 경우
  - summary: Hazardous items
    text: ⑦ 배송물이 화약류, 인화물질 등 위험한 물건인 경우
  - summary: Illegal items
    text: ⑧ 배송물이 밀수품, 군수품, 부정임산물 등 위법한 물건인 경우
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
name: Barogo
provenance_date: '2026-11-09'
provider_name: Barogo
provider_slug: barogo
slug: barogo-eligibility
source_date: '2026-11-09'
source_filename: barogo-eligibility.yml
source_heading: Eligibility
source_page: https://www.barogo.com/policy/delivery
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Barogo\naid: barogo\nurl: https://www.barogo.com/policy/delivery\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Items over 3 million won\n  text: ⑤ 배송물의 가액이 300만원을 초과하는 경우\n- summary: Hazardous items\n  text: ⑦ 배송물이 화약류, 인화물질 등 위험한 물건인 경우\n- summary: Illegal items\n  text: ⑧ 배송물이 밀수품, 군수품, 부정임산물 등 위법한 물건인 경우\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/barogo/eligibility/barogo-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 3 quoted statements, read from Barogo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Delivery
- Logistics
- Last Mile Delivery
- Food Delivery
- Couriers
- Fulfillment
- Order
- Webhook
- South Korea
- Transportation
- Marketplace
---
