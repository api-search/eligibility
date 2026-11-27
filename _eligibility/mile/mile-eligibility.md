---
api_specs:
- filename: mile-aramex-api-openapi.yml
  format: yaml
  label: Mile Aramex API
  slug: mile-aramex-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-aramex-api-openapi.yml
- filename: mile-customers-api-openapi.yml
  format: yaml
  label: Mile Customers API
  slug: mile-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-customers-api-openapi.yml
- filename: mile-debug-api-openapi.yml
  format: yaml
  label: Mile Debug API
  slug: mile-debug-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-debug-api-openapi.yml
- filename: mile-drivers-api-openapi.yml
  format: yaml
  label: Mile Drivers API
  slug: mile-drivers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-drivers-api-openapi.yml
- filename: mile-export-api-openapi.yml
  format: yaml
  label: Mile Export API
  slug: mile-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-export-api-openapi.yml
- filename: mile-login-api-openapi.yml
  format: yaml
  label: Mile Login API
  slug: mile-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-login-api-openapi.yml
- filename: mile-order-api-openapi.yml
  format: yaml
  label: Mile Order API
  slug: mile-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-order-api-openapi.yml
- filename: mile-order-optimization-api-openapi.yml
  format: yaml
  label: Mile Order Optimization API
  slug: mile-order-optimization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-order-optimization-api-openapi.yml
- filename: mile-order-webhook-api-openapi.yml
  format: yaml
  label: Mile Order Webhook API
  slug: mile-order-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-order-webhook-api-openapi.yml
- filename: mile-order-with-dynamic-merchant-api-openapi.yml
  format: yaml
  label: Mile Order With Dynamic Merchant API
  slug: mile-order-with-dynamic-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-order-with-dynamic-merchant-api-openapi.yml
- filename: mile-payment-terms-api-openapi.yml
  format: yaml
  label: Mile Payment Terms API
  slug: mile-payment-terms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-payment-terms-api-openapi.yml
- filename: mile-products-api-openapi.yml
  format: yaml
  label: Mile Products API
  slug: mile-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-products-api-openapi.yml
- filename: mile-promotion-bundle-api-openapi.yml
  format: yaml
  label: Mile Promotion Bundle API
  slug: mile-promotion-bundle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-promotion-bundle-api-openapi.yml
- filename: mile-routes-api-openapi.yml
  format: yaml
  label: Mile Routes API
  slug: mile-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-routes-api-openapi.yml
- filename: mile-settlement-webhook-api-openapi.yml
  format: yaml
  label: Mile Settlement Webhook API
  slug: mile-settlement-webhook-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-settlement-webhook-api-openapi.yml
- filename: mile-vehicles-api-openapi.yml
  format: yaml
  label: Mile Vehicles API
  slug: mile-vehicles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-vehicles-api-openapi.yml
- filename: mile-warehouse-inbound-orders-api-openapi.yml
  format: yaml
  label: Mile Warehouse Inbound Orders API
  slug: mile-warehouse-inbound-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-warehouse-inbound-orders-api-openapi.yml
- filename: mile-webhooks-api-openapi.yml
  format: yaml
  label: Mile Webhooks API
  slug: mile-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mile/openapi/mile-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: 'You warrant that: • You are 18 years of age or over.'
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
name: Mile
provenance_date: '2026-11-10'
provider_name: Mile
provider_slug: mile
slug: mile-eligibility
source_date: '2026-11-10'
source_filename: mile-eligibility.yml
source_heading: Eligibility
source_page: https://www.milenow.com/en/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mile\naid: mile\nurl: https://www.milenow.com/en/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'You warrant that: • You are 18 years of age or over.'\n"
source_yaml_url: https://artifacts.apis.io/mile/eligibility/mile-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Mile's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Supply Chain
- Last Mile Delivery
- Order Management
- Warehouse Management
- Transportation Management
- Fulfillment
- Shipping
- Webhook
- Route Optimization
---
