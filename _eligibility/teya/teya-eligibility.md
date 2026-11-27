---
api_specs:
- filename: teya-captures-api-openapi.yml
  format: yaml
  label: Teya Captures API
  slug: teya-captures-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-captures-api-openapi.yml
- filename: teya-dcc-api-openapi.yml
  format: yaml
  label: Teya DCC API
  slug: teya-dcc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-dcc-api-openapi.yml
- filename: teya-epos-registration-api-openapi.yml
  format: yaml
  label: Teya ePOS Registration API
  slug: teya-epos-registration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-epos-registration-api-openapi.yml
- filename: teya-hosted-checkout-api-openapi.yml
  format: yaml
  label: Teya Hosted Checkout API
  slug: teya-hosted-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-hosted-checkout-api-openapi.yml
- filename: teya-internal-api-openapi.yml
  format: yaml
  label: Teya '@internal' API
  slug: teya-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-internal-api-openapi.yml
- filename: teya-pay-at-table-api-openapi.yml
  format: yaml
  label: Teya Pay at Table API
  slug: teya-pay-at-table-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-pay-at-table-api-openapi.yml
- filename: teya-payment-requests-api-openapi.yml
  format: yaml
  label: Teya Payment Requests API
  slug: teya-payment-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-payment-requests-api-openapi.yml
- filename: teya-print-receipts-epos-api-openapi.yml
  format: yaml
  label: Teya Print Receipts (ePOS) API
  slug: teya-print-receipts-epos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-print-receipts-epos-api-openapi.yml
- filename: teya-public-api-openapi.yml
  format: yaml
  label: Teya '@public' API
  slug: teya-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-public-api-openapi.yml
- filename: teya-refunds-api-openapi.yml
  format: yaml
  label: Teya Refunds API
  slug: teya-refunds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-refunds-api-openapi.yml
- filename: teya-stores-api-openapi.yml
  format: yaml
  label: Teya Stores API
  slug: teya-stores-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-stores-api-openapi.yml
- filename: teya-terminals-api-openapi.yml
  format: yaml
  label: Teya Terminals API
  slug: teya-terminals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-terminals-api-openapi.yml
- filename: teya-tokens-api-openapi.yml
  format: yaml
  label: Teya Tokens API
  slug: teya-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-tokens-api-openapi.yml
- filename: teya-transactions-api-openapi.yml
  format: yaml
  label: Teya Transactions API
  slug: teya-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-transactions-api-openapi.yml
- filename: teya-pay-by-link-api-openapi.yml
  format: yaml
  label: Teya Pay by Link API
  slug: teya-pay-by-link-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/teya/openapi/teya-pay-by-link-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You agree not to access or use the Services in case it is illegal or not licensed for use in your location
  entity_types:
  - text: If you are using the Services on behalf of a business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Internal business use only
    text: (g) use the Services for any use other than internal business use
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
name: Teya
provenance_date: '2026-11-10'
provider_name: Teya
provider_slug: teya
slug: teya-eligibility
source_date: '2026-11-10'
source_filename: teya-eligibility.yml
source_heading: Eligibility
source_page: https://www.teya.com/legal/general-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Teya\naid: teya\nurl: https://www.teya.com/legal/general-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You agree not to access or use the Services in case it is illegal or not licensed for use in your location\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of a business\nrestricted_uses:\n- summary: Internal business use only\n  text: (g) use the Services for any use other than internal business use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/teya/eligibility/teya-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Teya's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Payment Processing
- Card Acquiring
- Online Payments
- Point-of-Sale
- E-Commerce
- Fintech
- Merchant Services
- Europe
- Card Machines
- Business Accounts
---
