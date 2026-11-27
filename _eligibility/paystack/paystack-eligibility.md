---
api_specs:
- filename: paystack-webhooks-asyncapi.yml
  format: yaml
  label: Paystack Webhooks
  slug: paystack-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/paystack/asyncapi/paystack-webhooks-asyncapi.yml
- filename: paystack-balance-api-openapi.yml
  format: yaml
  label: Paystack Balance API
  slug: paystack-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-balance-api-openapi.yml
- filename: paystack-bulk-charge-api-openapi.yml
  format: yaml
  label: Paystack Bulk Charge API
  slug: paystack-bulk-charge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-bulk-charge-api-openapi.yml
- filename: paystack-charge-api-openapi.yml
  format: yaml
  label: Paystack Charge API
  slug: paystack-charge-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-charge-api-openapi.yml
- filename: paystack-customer-api-openapi.yml
  format: yaml
  label: Paystack Customer API
  slug: paystack-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-customer-api-openapi.yml
- filename: paystack-dedicated-virtual-account-api-openapi.yml
  format: yaml
  label: Paystack Dedicated Virtual Account API
  slug: paystack-dedicated-virtual-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-dedicated-virtual-account-api-openapi.yml
- filename: paystack-dispute-api-openapi.yml
  format: yaml
  label: Paystack Dispute API
  slug: paystack-dispute-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-dispute-api-openapi.yml
- filename: paystack-integration-api-openapi.yml
  format: yaml
  label: Paystack Integration API
  slug: paystack-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-integration-api-openapi.yml
- filename: paystack-page-api-openapi.yml
  format: yaml
  label: Paystack Page API
  slug: paystack-page-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-page-api-openapi.yml
- filename: paystack-payment-request-api-openapi.yml
  format: yaml
  label: Paystack Payment Request API
  slug: paystack-payment-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-payment-request-api-openapi.yml
- filename: paystack-plan-api-openapi.yml
  format: yaml
  label: Paystack Plan API
  slug: paystack-plan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-plan-api-openapi.yml
- filename: paystack-product-api-openapi.yml
  format: yaml
  label: Paystack Product API
  slug: paystack-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-product-api-openapi.yml
- filename: paystack-refund-api-openapi.yml
  format: yaml
  label: Paystack Refund API
  slug: paystack-refund-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-refund-api-openapi.yml
- filename: paystack-settlement-api-openapi.yml
  format: yaml
  label: Paystack Settlement API
  slug: paystack-settlement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-settlement-api-openapi.yml
- filename: paystack-split-api-openapi.yml
  format: yaml
  label: Paystack Split API
  slug: paystack-split-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-split-api-openapi.yml
- filename: paystack-subscription-api-openapi.yml
  format: yaml
  label: Paystack Subscription API
  slug: paystack-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-subscription-api-openapi.yml
- filename: paystack-transaction-api-openapi.yml
  format: yaml
  label: Paystack Transaction API
  slug: paystack-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-transaction-api-openapi.yml
- filename: paystack-transfer-api-openapi.yml
  format: yaml
  label: Paystack Transfer API
  slug: paystack-transfer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-transfer-api-openapi.yml
- filename: paystack-transfer-recipient-api-openapi.yml
  format: yaml
  label: Paystack Transfer Recipient API
  slug: paystack-transfer-recipient-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-transfer-recipient-api-openapi.yml
- filename: paystack-verification-api-openapi.yml
  format: yaml
  label: Paystack Verification API
  slug: paystack-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-verification-api-openapi.yml
- filename: paystack-sub-account-api-openapi.yml
  format: yaml
  label: Paystack Sub Account API
  slug: paystack-sub-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystack/openapi/paystack-sub-account-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: While our services are primarily designed for businesses and organisations
    type: business
  minimum_age:
    text: Our website and services are not directed to children under 18.
    value: '18'
  restricted_uses:
  - summary: Gambling and games with prizes
    text: involve gambling, gaming and/or any other activity with an entry fee and a prize
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
name: Paystack
provenance_date: '2026-11-10'
provider_name: Paystack
provider_slug: paystack
slug: paystack-eligibility
source_date: '2026-11-10'
source_filename: paystack-eligibility.yml
source_heading: Eligibility
source_page: https://paystack.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Paystack\naid: paystack\nurl: https://paystack.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: While our services are primarily designed for businesses and organisations\nrestricted_uses:\n- summary: Gambling and games with prizes\n  text: involve gambling, gaming and/or any other activity with an entry fee and a prize\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Our website and services are not directed to children under 18.\n"
source_yaml_url: https://artifacts.apis.io/paystack/eligibility/paystack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Paystack's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Africa
- Fintech
- Recurring Billing
- Marketplace
- Payouts
- Mobile Money
- Stripe
---
