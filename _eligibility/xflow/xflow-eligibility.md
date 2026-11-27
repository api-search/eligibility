---
api_specs:
- filename: xflow-accounts-api-openapi.yml
  format: yaml
  label: Xflow Accounts API
  slug: xflow-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-accounts-api-openapi.yml
- filename: xflow-addresses-api-openapi.yml
  format: yaml
  label: Xflow Addresses API
  slug: xflow-addresses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-addresses-api-openapi.yml
- filename: xflow-balance-api-openapi.yml
  format: yaml
  label: Xflow Balance API
  slug: xflow-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-balance-api-openapi.yml
- filename: xflow-deposits-api-openapi.yml
  format: yaml
  label: Xflow Deposits API
  slug: xflow-deposits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-deposits-api-openapi.yml
- filename: xflow-events-api-openapi.yml
  format: yaml
  label: Xflow Events API
  slug: xflow-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-events-api-openapi.yml
- filename: xflow-files-api-openapi.yml
  format: yaml
  label: Xflow Files API
  slug: xflow-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-files-api-openapi.yml
- filename: xflow-payments-api-openapi.yml
  format: yaml
  label: Xflow Payments API
  slug: xflow-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-payments-api-openapi.yml
- filename: xflow-payouts-api-openapi.yml
  format: yaml
  label: Xflow Payouts API
  slug: xflow-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-payouts-api-openapi.yml
- filename: xflow-persons-api-openapi.yml
  format: yaml
  label: Xflow Persons API
  slug: xflow-persons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-persons-api-openapi.yml
- filename: xflow-quotes-api-openapi.yml
  format: yaml
  label: Xflow Quotes API
  slug: xflow-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-quotes-api-openapi.yml
- filename: xflow-receivables-api-openapi.yml
  format: yaml
  label: Xflow Receivables API
  slug: xflow-receivables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-receivables-api-openapi.yml
- filename: xflow-transfers-api-openapi.yml
  format: yaml
  label: Xflow Transfers API
  slug: xflow-transfers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-transfers-api-openapi.yml
- filename: xflow-account-settings-api-openapi.yml
  format: yaml
  label: Xflow Account Settings API
  slug: xflow-account-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-account-settings-api-openapi.yml
- filename: xflow-balance-transactions-api-openapi.yml
  format: yaml
  label: Xflow Balance Transactions API
  slug: xflow-balance-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-balance-transactions-api-openapi.yml
- filename: xflow-exchange-rates-api-openapi.yml
  format: yaml
  label: Xflow Exchange Rates API
  slug: xflow-exchange-rates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-exchange-rates-api-openapi.yml
- filename: xflow-fee-plans-api-openapi.yml
  format: yaml
  label: Xflow Fee Plans API
  slug: xflow-fee-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-fee-plans-api-openapi.yml
- filename: xflow-payment-links-api-openapi.yml
  format: yaml
  label: Xflow Payment Links API
  slug: xflow-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-payment-links-api-openapi.yml
- filename: xflow-webhook-endpoints-api-openapi.yml
  format: yaml
  label: Xflow Webhook Endpoints API
  slug: xflow-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/xflow/openapi/xflow-webhook-endpoints-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: available only to entities and persons who have reached the age of legal majority and are competent to enter into a legally binding agreement(s) under the applicable law
    type: business
  minimum_age:
    text: available only to entities and persons who have reached the age of legal majority
    value: null
  restricted_uses:
  - summary: Unlawful purposes and prohibited content
    text: use the Website for any unlawful purpose
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
name: Xflow
provenance_date: '2026-11-10'
provider_name: Xflow
provider_slug: xflow
slug: xflow-eligibility
source_date: '2026-11-10'
source_filename: xflow-eligibility.yml
source_heading: Eligibility
source_page: https://docs.xflowpay.com/website-tou
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xflow\naid: xflow\nurl: https://docs.xflowpay.com/website-tou\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: available only to entities and persons who have reached the age of legal majority and are competent to enter\n    into a legally binding agreement(s) under the applicable law\nrestricted_uses:\n- summary: Unlawful purposes and prohibited content\n  text: use the Website for any unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: available only\
  \ to entities and persons who have reached the age of legal majority\n"
source_yaml_url: https://artifacts.apis.io/xflow/eligibility/xflow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Xflow's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Cross-Border Payments
- Fintech
- India
- Foreign Exchange
- Invoicing
- Payouts
---
