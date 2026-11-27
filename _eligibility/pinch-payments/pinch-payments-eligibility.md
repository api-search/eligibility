---
api_specs:
- filename: pinch-payments-connect-api-openapi.yml
  format: yaml
  label: Pinch Payments Connect API
  slug: pinch-payments-connect-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-connect-api-openapi.yml
- filename: pinch-payments-contacts-api-openapi.yml
  format: yaml
  label: Pinch Payments Contacts API
  slug: pinch-payments-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-contacts-api-openapi.yml
- filename: pinch-payments-events-api-openapi.yml
  format: yaml
  label: Pinch Payments Events API
  slug: pinch-payments-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-events-api-openapi.yml
- filename: pinch-payments-fees-api-openapi.yml
  format: yaml
  label: Pinch Payments Fees API
  slug: pinch-payments-fees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-fees-api-openapi.yml
- filename: pinch-payments-health-api-openapi.yml
  format: yaml
  label: Pinch Payments Health API
  slug: pinch-payments-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-health-api-openapi.yml
- filename: pinch-payments-merchant-financial-data-api-openapi.yml
  format: yaml
  label: Pinch Payments Merchant Financial Data API
  slug: pinch-payments-merchant-financial-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-merchant-financial-data-api-openapi.yml
- filename: pinch-payments-merchants-api-openapi.yml
  format: yaml
  label: Pinch Payments Merchants API
  slug: pinch-payments-merchants-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-merchants-api-openapi.yml
- filename: pinch-payments-payers-api-openapi.yml
  format: yaml
  label: Pinch Payments Payers API
  slug: pinch-payments-payers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-payers-api-openapi.yml
- filename: pinch-payments-payment-links-api-openapi.yml
  format: yaml
  label: Pinch Payments Payment Links API
  slug: pinch-payments-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-payment-links-api-openapi.yml
- filename: pinch-payments-payments-api-openapi.yml
  format: yaml
  label: Pinch Payments API
  slug: pinch-payments-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-payments-api-openapi.yml
- filename: pinch-payments-plans-api-openapi.yml
  format: yaml
  label: Pinch Payments Plans API
  slug: pinch-payments-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-plans-api-openapi.yml
- filename: pinch-payments-refund-api-openapi.yml
  format: yaml
  label: Pinch Payments Refund API
  slug: pinch-payments-refund-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-refund-api-openapi.yml
- filename: pinch-payments-refunds-api-openapi.yml
  format: yaml
  label: Pinch Payments Refunds API
  slug: pinch-payments-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-refunds-api-openapi.yml
- filename: pinch-payments-subscriptions-api-openapi.yml
  format: yaml
  label: Pinch Payments Subscriptions API
  slug: pinch-payments-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-subscriptions-api-openapi.yml
- filename: pinch-payments-tokens-api-openapi.yml
  format: yaml
  label: Pinch Payments Tokens API
  slug: pinch-payments-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-tokens-api-openapi.yml
- filename: pinch-payments-transfers-api-openapi.yml
  format: yaml
  label: Pinch Payments Transfers API
  slug: pinch-payments-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-transfers-api-openapi.yml
- filename: pinch-payments-webhooks-api-openapi.yml
  format: yaml
  label: Pinch Payments Webhooks API
  slug: pinch-payments-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/pinch-payments/openapi/pinch-payments-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: Our site is directed to people residing in Australia.
  entity_types:
  - text: If you are a business, these terms of use, its subject matter and its formation (and any non-contractual disputes or claims) are governed by Australian law.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Malicious or unauthorised activity
    text: You must not misuse our site by knowingly introducing viruses, trojans, worms, logic bombs or other material which is malicious or technologically harmful.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need to register with us to fully access the service and provide as a minimum your proper name, e-mail address, and a password.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pinch Payments
provenance_date: '2026-11-10'
provider_name: Pinch Payments
provider_slug: pinch-payments
slug: pinch-payments-eligibility
source_date: '2026-11-10'
source_filename: pinch-payments-eligibility.yml
source_heading: Eligibility
source_page: https://getpinch.com.au/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pinch Payments\naid: pinch-payments\nurl: https://getpinch.com.au/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: Our site is directed to people residing in Australia.\nentity_types:\n- type: business\n  text: If you are a business, these terms of use, its subject matter and its formation (and any non-contractual\n    disputes or claims) are governed by Australian law.\nrestricted_uses:\n- summary: Malicious or unauthorised activity\n  text: You must not misuse our site by knowingly introducing viruses, trojans, worms, logic bombs or other material\n    which is\
  \ malicious or technologically harmful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need to register with us to fully access the service and provide as a minimum your proper name, e-mail\n    address, and a password.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pinch-payments/eligibility/pinch-payments-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Pinch Payments's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Australia
- Payment Gateway
- Payment Processing
- Direct Debit
- Card Payments
- Subscription
- Billing
- Payment Facilitator
- Account-to-Account
- New Zealand
---
