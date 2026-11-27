---
api_specs:
- filename: mpesa-account-balance-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) Account Balance API
  slug: mpesa-account-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-account-balance-api-openapi.yml
- filename: mpesa-authorization-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) Authorization API
  slug: mpesa-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-authorization-api-openapi.yml
- filename: mpesa-b2c-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) B2C API
  slug: mpesa-b2c-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-b2c-api-openapi.yml
- filename: mpesa-c2b-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) C2B API
  slug: mpesa-c2b-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-c2b-api-openapi.yml
- filename: mpesa-dynamic-qr-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) Dynamic QR API
  slug: mpesa-dynamic-qr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-dynamic-qr-api-openapi.yml
- filename: mpesa-m-pesa-express-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) M-Pesa Express API
  slug: mpesa-m-pesa-express-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-m-pesa-express-api-openapi.yml
- filename: mpesa-reversal-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) Reversal API
  slug: mpesa-reversal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-reversal-api-openapi.yml
- filename: mpesa-standing-order-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) Standing Order API
  slug: mpesa-standing-order-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-standing-order-api-openapi.yml
- filename: mpesa-tax-remittance-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) Tax Remittance API
  slug: mpesa-tax-remittance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-tax-remittance-api-openapi.yml
- filename: mpesa-transaction-status-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) Transaction Status API
  slug: mpesa-transaction-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-transaction-status-api-openapi.yml
- filename: mpesa-b2-b-api-openapi.yml
  format: yaml
  label: M-Pesa (Safaricom Daraja) B2B API
  slug: mpesa-b2-b-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mpesa/openapi/mpesa-b2-b-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Register and create an account as either a company or individual and login to get started.
    type: individual
  - text: Register and create an account as either a company or individual and login to get started.
    type: business
  minimum_age:
    text: null
    value: null
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
name: M-Pesa (Safaricom Daraja)
provenance_date: '2026-11-10'
provider_name: M-Pesa (Safaricom Daraja)
provider_slug: mpesa
slug: mpesa-eligibility
source_date: '2026-11-10'
source_filename: mpesa-eligibility.yml
source_heading: Eligibility
source_page: https://developer.safaricom.co.ke/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: M-Pesa (Safaricom Daraja)\naid: mpesa\nurl: https://developer.safaricom.co.ke/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Register and create an account as either a company or individual and login to get started.\n- type: business\n  text: Register and create an account as either a company or individual and login to get started.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mpesa/eligibility/mpesa-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from M-Pesa (Safaricom Daraja)'s own page on 2026-11-10.
synthetic: false
tags:
- Mobile Money
- Payments
- Fintech
- Kenya
- Africa
- M-PESA
---
