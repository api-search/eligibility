---
api_specs:
- filename: coinflow-authentication-api-openapi.yml
  format: yaml
  label: Coinflow Authentication API
  slug: coinflow-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-authentication-api-openapi.yml
- filename: coinflow-checkout-api-openapi.yml
  format: yaml
  label: Coinflow Checkout API
  slug: coinflow-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-checkout-api-openapi.yml
- filename: coinflow-customers-api-openapi.yml
  format: yaml
  label: Coinflow Customers API
  slug: coinflow-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-customers-api-openapi.yml
- filename: coinflow-events-api-openapi.yml
  format: yaml
  label: Coinflow Events API
  slug: coinflow-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-events-api-openapi.yml
- filename: coinflow-marketplace-api-openapi.yml
  format: yaml
  label: Coinflow Marketplace API
  slug: coinflow-marketplace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-marketplace-api-openapi.yml
- filename: coinflow-merchant-api-openapi.yml
  format: yaml
  label: Coinflow Merchant API
  slug: coinflow-merchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-merchant-api-openapi.yml
- filename: coinflow-merchantsubscription-api-openapi.yml
  format: yaml
  label: Coinflow Merchant Subscription API
  slug: coinflow-merchantsubscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-merchantsubscription-api-openapi.yml
- filename: coinflow-redeem-api-openapi.yml
  format: yaml
  label: Coinflow Redeem API
  slug: coinflow-redeem-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-redeem-api-openapi.yml
- filename: coinflow-refund-api-openapi.yml
  format: yaml
  label: Coinflow Refund API
  slug: coinflow-refund-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-refund-api-openapi.yml
- filename: coinflow-submerchant-api-openapi.yml
  format: yaml
  label: Coinflow Sub Merchant API
  slug: coinflow-submerchant-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-submerchant-api-openapi.yml
- filename: coinflow-subscription-api-openapi.yml
  format: yaml
  label: Coinflow Subscription API
  slug: coinflow-subscription-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-subscription-api-openapi.yml
- filename: coinflow-utilities-api-openapi.yml
  format: yaml
  label: Coinflow Utilities API
  slug: coinflow-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-utilities-api-openapi.yml
- filename: coinflow-withdraw-api-openapi.yml
  format: yaml
  label: Coinflow Withdraw API
  slug: coinflow-withdraw-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-withdraw-api-openapi.yml
- filename: coinflow-merchantaccounts-api-openapi.yml
  format: yaml
  label: Coinflow Merchant Accounts API
  slug: coinflow-merchantaccounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-merchantaccounts-api-openapi.yml
- filename: coinflow-card-tokenization-api-openapi.yml
  format: yaml
  label: Coinflow Card Tokenization API
  slug: coinflow-card-tokenization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coinflow/openapi/coinflow-card-tokenization-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Prior to using certain Services and from time to time thereafter, Customer must successfully complete Customer Due Diligence.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coinflow
provenance_date: '2026-11-09'
provider_name: Coinflow
provider_slug: coinflow
slug: coinflow-eligibility
source_date: '2026-11-09'
source_filename: coinflow-eligibility.yml
source_heading: Eligibility
source_page: https://coinflow.cash/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coinflow\naid: coinflow\nurl: https://coinflow.cash/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Prior to using certain Services and from time to time thereafter, Customer must successfully complete Customer\n    Due Diligence.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coinflow/eligibility/coinflow-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from Coinflow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Payments
- Stablecoins
- USDC
- Checkout
- Payouts
- Marketplace
- Web3
- Fintech
---
