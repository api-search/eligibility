---
api_specs:
- filename: xrpay-connected-account-api-openapi.yml
  format: yaml
  label: XRPay Connected account API
  slug: xrpay-connected-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-connected-account-api-openapi.yml
- filename: xrpay-payment-intents-api-openapi.yml
  format: yaml
  label: XRPay Payment intents API
  slug: xrpay-payment-intents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-payment-intents-api-openapi.yml
- filename: xrpay-payouts-api-openapi.yml
  format: yaml
  label: XRPay Payouts API
  slug: xrpay-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-payouts-api-openapi.yml
- filename: xrpay-payroll-api-openapi.yml
  format: yaml
  label: XRPay Payroll API
  slug: xrpay-payroll-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-payroll-api-openapi.yml
- filename: xrpay-refunds-api-openapi.yml
  format: yaml
  label: XRPay Refunds API
  slug: xrpay-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-refunds-api-openapi.yml
- filename: xrpay-sandbox-api-openapi.yml
  format: yaml
  label: XRPay Sandbox API
  slug: xrpay-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-sandbox-api-openapi.yml
- filename: xrpay-webhooks-api-openapi.yml
  format: yaml
  label: XRPay Webhooks API
  slug: xrpay-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xrpay/openapi/xrpay-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Fiat withdrawal service is available globally, subject to the supported countries and currencies of our settlement partner Bridge.xyz.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited financial activities
    text: Prohibited activities include structuring, sanctions evasion, and any use that violates applicable law.
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
name: XRPay
provenance_date: '2026-11-10'
provider_name: XRPay
provider_slug: xrpay
slug: xrpay-eligibility
source_date: '2026-11-10'
source_filename: xrpay-eligibility.yml
source_heading: Eligibility
source_page: https://www.xrpay.it/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: XRPay\naid: xrpay\nurl: https://www.xrpay.it/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Fiat withdrawal service is available globally, subject to the supported countries and currencies of our\n    settlement partner Bridge.xyz.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited financial activities\n  text: Prohibited activities include structuring, sanctions evasion, and any use that violates applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/xrpay/eligibility/xrpay-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from XRPay's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Merchant Payments
- Refunds
- Webhook
- Fintech
---
