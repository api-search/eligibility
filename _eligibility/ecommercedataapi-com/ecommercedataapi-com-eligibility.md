---
api_specs:
- filename: ecommercedataapi-com-amazon-keywords-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Amazon Keywords API
  slug: ecommercedataapi-com-amazon-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-amazon-keywords-api-openapi.yml
- filename: ecommercedataapi-com-amazon-markets-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Amazon Markets API
  slug: ecommercedataapi-com-amazon-markets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-amazon-markets-api-openapi.yml
- filename: ecommercedataapi-com-amazon-products-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Amazon Products API
  slug: ecommercedataapi-com-amazon-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-amazon-products-api-openapi.yml
- filename: ecommercedataapi-com-amazon-traffic-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Amazon Traffic API
  slug: ecommercedataapi-com-amazon-traffic-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-amazon-traffic-api-openapi.yml
- filename: ecommercedataapi-com-global-trademarks-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Global Trademarks API
  slug: ecommercedataapi-com-global-trademarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-global-trademarks-api-openapi.yml
- filename: ecommercedataapi-com-tools-api-openapi.yml
  format: yaml
  label: ecommercedataapi-com Tools API
  slug: ecommercedataapi-com-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ecommercedataapi-com/openapi/ecommercedataapi-com-tools-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 您必须年满 18 周岁并具备订立有约束力合同的能力，方可注册账户或使用本服务。
    type: individual
  - text: 本服务面向 商业用途。
    type: business
  minimum_age:
    text: 您必须年满 18 周岁
    value: '18'
  restricted_uses:
  - summary: Illegal activity
    text: 将 API 用于违法活动
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
name: ecommercedataapi-com
provenance_date: '2026-11-09'
provider_name: ecommercedataapi-com
provider_slug: ecommercedataapi-com
slug: ecommercedataapi-com-eligibility
source_date: '2026-11-09'
source_filename: ecommercedataapi-com-eligibility.yml
source_heading: Eligibility
source_page: https://ecommercedataapi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ecommercedataapi-com\naid: ecommercedataapi-com\nurl: https://ecommercedataapi.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 您必须年满 18 周岁并具备订立有约束力合同的能力，方可注册账户或使用本服务。\n- type: business\n  text: 本服务面向 商业用途。\nrestricted_uses:\n- summary: Illegal activity\n  text: 将 API 用于违法活动\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 您必须年满 18 周岁\n"
source_yaml_url: https://artifacts.apis.io/ecommercedataapi-com/eligibility/ecommercedataapi-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ecommercedataapi-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Data
- Amazon
- Market Research
---
