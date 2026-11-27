---
api_specs:
- filename: metrilo-category-api-openapi.yml
  format: yaml
  label: Metrilo Category API
  slug: metrilo-category-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metrilo/openapi/metrilo-category-api-openapi.yml
- filename: metrilo-customer-api-openapi.yml
  format: yaml
  label: Metrilo Customer API
  slug: metrilo-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metrilo/openapi/metrilo-customer-api-openapi.yml
- filename: metrilo-order-api-openapi.yml
  format: yaml
  label: Metrilo Order API
  slug: metrilo-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metrilo/openapi/metrilo-order-api-openapi.yml
- filename: metrilo-product-api-openapi.yml
  format: yaml
  label: Metrilo Product API
  slug: metrilo-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/metrilo/openapi/metrilo-product-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be a minimum age of 18 to register on and use the Service.
    type: individual
  - text: Where we provide an organisation with a number of user licenses for the Service these must be adhered to.
    type: business
  minimum_age:
    text: You must be a minimum age of 18 to register on and use the Service.
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
name: Metrilo
provenance_date: '2026-11-10'
provider_name: Metrilo
provider_slug: metrilo
slug: metrilo-eligibility
source_date: '2026-11-10'
source_filename: metrilo-eligibility.yml
source_heading: Eligibility
source_page: https://www.metrilo.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Metrilo\naid: metrilo\nurl: https://www.metrilo.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be a minimum age of 18 to register on and use the Service.\n- type: business\n  text: Where we provide an organisation with a number of user licenses for the Service these must be adhered to.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be a minimum age of 18 to register on and use the Service.\n"
source_yaml_url: https://artifacts.apis.io/metrilo/eligibility/metrilo-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Metrilo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Analytics
- CRM
- Email Marketing
- Customer Retention
- Tracking
- Marketing
---
