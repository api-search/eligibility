---
api_specs:
- filename: payjoy-carts-api-openapi.yml
  format: yaml
  label: PayJoy Carts API
  slug: payjoy-carts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-carts-api-openapi.yml
- filename: payjoy-down-payments-api-openapi.yml
  format: yaml
  label: PayJoy Down Payments API
  slug: payjoy-down-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-down-payments-api-openapi.yml
- filename: payjoy-merchants-api-openapi.yml
  format: yaml
  label: PayJoy Merchants API
  slug: payjoy-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-merchants-api-openapi.yml
- filename: payjoy-reconciliation-api-openapi.yml
  format: yaml
  label: PayJoy Reconciliation API
  slug: payjoy-reconciliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-reconciliation-api-openapi.yml
- filename: payjoy-repayments-api-openapi.yml
  format: yaml
  label: PayJoy Repayments API
  slug: payjoy-repayments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-repayments-api-openapi.yml
- filename: payjoy-salesclerks-api-openapi.yml
  format: yaml
  label: PayJoy SalesClerks API
  slug: payjoy-salesclerks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-salesclerks-api-openapi.yml
- filename: payjoy-status-api-openapi.yml
  format: yaml
  label: PayJoy Status API
  slug: payjoy-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-status-api-openapi.yml
- filename: payjoy-vouchers-api-openapi.yml
  format: yaml
  label: PayJoy Vouchers API
  slug: payjoy-vouchers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/payjoy/openapi/payjoy-vouchers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using one or more Products on behalf of a company, entity or organization (each a “Subscribing Entity”), you represent and warrant that you are an authorized representative of such Subscribing Entity
    type: business
  minimum_age:
    text: The Products are not intended for use by persons under the age of 13.
    value: '13'
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
name: PayJoy
provenance_date: '2026-11-10'
provider_name: PayJoy
provider_slug: payjoy
slug: payjoy-eligibility
source_date: '2026-11-10'
source_filename: payjoy-eligibility.yml
source_heading: Eligibility
source_page: https://www.payjoy.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayJoy\naid: payjoy\nurl: https://www.payjoy.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using one or more Products on behalf of a company, entity or organization (each a “Subscribing\n    Entity”), you represent and warrant that you are an authorized representative of such Subscribing Entity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Products are not intended for use by persons under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/payjoy/eligibility/payjoy-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from PayJoy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Lending
- Buy Now Pay Later
- Point-of-Sale
- Emerging Markets
- Financial Inclusion
- Partner API
---
