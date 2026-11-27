---
api_specs:
- filename: paystand-balances-api-openapi.yml
  format: yaml
  label: PayStand Balances API
  slug: paystand-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystand/openapi/paystand-balances-api-openapi.yml
- filename: paystand-banks-api-openapi.yml
  format: yaml
  label: PayStand Banks API
  slug: paystand-banks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystand/openapi/paystand-banks-api-openapi.yml
- filename: paystand-oauth-api-openapi.yml
  format: yaml
  label: PayStand OAuth API
  slug: paystand-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystand/openapi/paystand-oauth-api-openapi.yml
- filename: paystand-payers-api-openapi.yml
  format: yaml
  label: PayStand Payers API
  slug: paystand-payers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystand/openapi/paystand-payers-api-openapi.yml
- filename: paystand-payments-api-openapi.yml
  format: yaml
  label: PayStand Payments API
  slug: paystand-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystand/openapi/paystand-payments-api-openapi.yml
- filename: paystand-refunds-api-openapi.yml
  format: yaml
  label: PayStand Refunds API
  slug: paystand-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystand/openapi/paystand-refunds-api-openapi.yml
- filename: paystand-transfers-api-openapi.yml
  format: yaml
  label: PayStand Transfers API
  slug: paystand-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystand/openapi/paystand-transfers-api-openapi.yml
- filename: paystand-withdrawals-api-openapi.yml
  format: yaml
  label: PayStand Withdrawals API
  slug: paystand-withdrawals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/paystand/openapi/paystand-withdrawals-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To be eligible to use Paystand, you must be at least 18 years old and located in the United States of America.
  entity_types:
  - text: You may register for the Service only as a sole proprietor or as a business organization
    type: business
  minimum_age:
    text: To be eligible to use Paystand, you must be at least 18 years old and located in the United States of America.
    value: '18'
  restricted_uses:
  - summary: No personal, family or home use
    text: may not use Paystand for personal, family, or home purposes.
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
name: PayStand
provenance_date: '2026-11-10'
provider_name: PayStand
provider_slug: paystand
slug: paystand-eligibility
source_date: '2026-11-10'
source_filename: paystand-eligibility.yml
source_heading: Eligibility
source_page: https://www.paystand.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayStand\naid: paystand\nurl: https://www.paystand.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To be eligible to use Paystand, you must be at least 18 years old and located in the United States of America.\nentity_types:\n- type: business\n  text: You may register for the Service only as a sole proprietor or as a business organization\nrestricted_uses:\n- summary: No personal, family or home use\n  text: may not use Paystand for personal, family, or home purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '18'\n  text: To be eligible to use Paystand, you must be at least 18 years old and located in the United States of America.\n"
source_yaml_url: https://artifacts.apis.io/paystand/eligibility/paystand-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from PayStand's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- B2B Payments
- Accounts Receivable
- Accounts Payable
- Fintech
- Blockchain
- ACH
- Billing
- Checkout
---
