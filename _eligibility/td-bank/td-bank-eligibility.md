---
api_specs:
- filename: td-bank-transactions-api-openapi.yml
  format: yaml
  label: TD Bank Transactions API
  slug: transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-transactions-api-openapi.yml
- filename: td-bank-statements-api-openapi.yml
  format: yaml
  label: TD Bank Statements API
  slug: statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-statements-api-openapi.yml
- filename: td-bank-tax-forms-api-openapi.yml
  format: yaml
  label: TD Bank Tax Forms API
  slug: tax-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-tax-forms-api-openapi.yml
- filename: td-bank-rewards-api-openapi.yml
  format: yaml
  label: TD Bank Rewards API
  slug: rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-rewards-api-openapi.yml
- filename: td-bank-notifications-api-openapi.yml
  format: yaml
  label: TD Bank Notifications API
  slug: notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-notifications-api-openapi.yml
- filename: td-bank-accounts-api-openapi.yml
  format: yaml
  label: TD Bank Accounts API
  slug: td-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-accounts-api-openapi.yml
- filename: td-bank-apps-api-openapi.yml
  format: yaml
  label: TD Bank Apps API
  slug: td-bank-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-apps-api-openapi.yml
- filename: td-bank-bill-payments-api-openapi.yml
  format: yaml
  label: TD Bank Bill Payments API
  slug: td-bank-bill-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-bill-payments-api-openapi.yml
- filename: td-bank-clusters-api-openapi.yml
  format: yaml
  label: TD Bank Clusters API
  slug: td-bank-clusters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-clusters-api-openapi.yml
- filename: td-bank-consents-api-openapi.yml
  format: yaml
  label: TD Bank Consents API
  slug: td-bank-consents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-consents-api-openapi.yml
- filename: td-bank-customers-api-openapi.yml
  format: yaml
  label: TD Bank Customers API
  slug: td-bank-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-customers-api-openapi.yml
- filename: td-bank-payees-api-openapi.yml
  format: yaml
  label: TD Bank Payees API
  slug: td-bank-payees-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-payees-api-openapi.yml
- filename: td-bank-service-tokens-api-openapi.yml
  format: yaml
  label: TD Bank Service Tokens API
  slug: td-bank-service-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-service-tokens-api-openapi.yml
- filename: td-bank-subscriptions-api-openapi.yml
  format: yaml
  label: TD Bank Subscriptions API
  slug: td-bank-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-subscriptions-api-openapi.yml
- filename: td-bank-tokens-api-openapi.yml
  format: yaml
  label: TD Bank Tokens API
  slug: td-bank-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/td-bank/openapi/td-bank-tokens-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Our online services are not intended for children under 13 years of age.
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
name: TD Bank
provenance_date: '2026-11-10'
provider_name: TD Bank
provider_slug: td-bank
slug: td-bank-eligibility
source_date: '2026-11-10'
source_filename: td-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.td.com/us/en/personal-banking/privacy
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TD Bank\naid: td-bank\nurl: https://www.td.com/us/en/personal-banking/privacy\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Our online services are not intended for children under 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/td-bank/eligibility/td-bank-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from TD Bank's own page on 2026-11-10.
synthetic: false
tags:
- Account Aggregation
- AML
- Akoya
- Banking
- Bank Secrecy Act
- Bill Payments
- Consent
- Consumer Banking
- FDX
- Financial Services
- Merchant Solutions
- Notification
- Open Banking
- Payments
- Rewards
- Tax Forms
- Token Management
- Transaction
---
