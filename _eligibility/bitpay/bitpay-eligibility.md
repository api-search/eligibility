---
api_specs:
- filename: bitpay-bills-api-openapi.yml
  format: yaml
  label: BitPay Bills API
  slug: bitpay-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-bills-api-openapi.yml
- filename: bitpay-payouts-api-openapi.yml
  format: yaml
  label: BitPay Payouts API
  slug: bitpay-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-payouts-api-openapi.yml
- filename: bitpay-refunds-api-openapi.yml
  format: yaml
  label: BitPay Refunds API
  slug: bitpay-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-refunds-api-openapi.yml
- filename: bitpay-settlements-api-openapi.yml
  format: yaml
  label: BitPay Settlements API
  slug: bitpay-settlements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-settlements-api-openapi.yml
- filename: bitpay-rates-api-openapi.yml
  format: yaml
  label: BitPay Rates API
  slug: bitpay-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-rates-api-openapi.yml
- filename: bitpay-ledgers-api-openapi.yml
  format: yaml
  label: BitPay Ledgers API
  slug: bitpay-ledgers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-ledgers-api-openapi.yml
- filename: bitpay-bills-api-openapi.yml
  format: yaml
  label: BitPay Bills API
  slug: bitpay-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-bills-api-openapi.yml
- filename: bitpay-invoices-api-openapi.yml
  format: yaml
  label: BitPay Invoices API
  slug: bitpay-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-invoices-api-openapi.yml
- filename: bitpay-ledgers-api-openapi.yml
  format: yaml
  label: BitPay Ledgers API
  slug: bitpay-ledgers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-ledgers-api-openapi.yml
- filename: bitpay-payouts-api-openapi.yml
  format: yaml
  label: BitPay Payouts API
  slug: bitpay-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-payouts-api-openapi.yml
- filename: bitpay-rates-api-openapi.yml
  format: yaml
  label: BitPay Rates API
  slug: bitpay-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-rates-api-openapi.yml
- filename: bitpay-refunds-api-openapi.yml
  format: yaml
  label: BitPay Refunds API
  slug: bitpay-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-refunds-api-openapi.yml
- filename: bitpay-settlements-api-openapi.yml
  format: yaml
  label: BitPay Settlements API
  slug: bitpay-settlements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bitpay/openapi/bitpay-settlements-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Unless you are located in one of the countries listed in the next sentence your relationship pursuant to these Terms is with BitPay, Inc., a Delaware, USA corporation
  entity_types:
  - text: The Acceptance Services are only available to (i) businesses that sell products or services
    type: business
  - text: (ii) registered charitable organizations that accept donations
    type: nonprofit
  minimum_age:
    text: The individual accepting these terms on behalf of the Merchant or Donee, as applicable, is of the age of majority
    value: null
  restricted_uses:
  - summary: Restricted businesses (need express authorization)
    text: If you fall into or your business is related to, offer or transact in any of the following categories, you will only be allowed to transact as expressly authorized by us
  - summary: Gambling only where lawful
    text: Transactions involving gambling or any activity requiring an entry fee and a prize
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
name: BitPay
provenance_date: '2026-11-09'
provider_name: BitPay
provider_slug: bitpay
slug: bitpay-eligibility
source_date: '2026-11-09'
source_filename: bitpay-eligibility.yml
source_heading: Eligibility
source_page: https://www.bitpay.com/inc/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BitPay\naid: bitpay\nurl: https://www.bitpay.com/inc/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Unless you are located in one of the countries listed in the next sentence your relationship pursuant to\n    these Terms is with BitPay, Inc., a Delaware, USA corporation\nentity_types:\n- type: business\n  text: The Acceptance Services are only available to (i) businesses that sell products or services\n- type: nonprofit\n  text: (ii) registered charitable organizations that accept donations\nrestricted_uses:\n- summary: Restricted businesses\
  \ (need express authorization)\n  text: If you fall into or your business is related to, offer or transact in any of the following categories, you\n    will only be allowed to transact as expressly authorized by us\n- summary: Gambling only where lawful\n  text: Transactions involving gambling or any activity requiring an entry fee and a prize\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: The individual accepting these terms on behalf of the Merchant or Donee, as applicable, is of the age of\n    majority\n"
source_yaml_url: https://artifacts.apis.io/bitpay/eligibility/bitpay-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from BitPay's own page on 2026-11-09.
synthetic: false
tags:
- Cryptocurrency
- Payments
- Bitcoin
- Blockchain
- Invoices
- Payouts
- Settlement
---
