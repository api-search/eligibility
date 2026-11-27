---
api_specs:
- filename: qualpay-account-updater-api-openapi.yml
  format: yaml
  label: Qualpay Account Updater API
  slug: qualpay-account-updater-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-account-updater-api-openapi.yml
- filename: qualpay-application-boarding-api-openapi.yml
  format: yaml
  label: Qualpay Application Boarding API
  slug: qualpay-application-boarding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-application-boarding-api-openapi.yml
- filename: qualpay-checkout-api-openapi.yml
  format: yaml
  label: Qualpay Checkout API
  slug: qualpay-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-checkout-api-openapi.yml
- filename: qualpay-customer-vault-api-openapi.yml
  format: yaml
  label: Qualpay Customer Vault API
  slug: qualpay-customer-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-customer-vault-api-openapi.yml
- filename: qualpay-disputes-v0-5-api-openapi.yml
  format: yaml
  label: Qualpay Disputes v0.5 API
  slug: qualpay-disputes-v0-5-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-disputes-v0-5-api-openapi.yml
- filename: qualpay-disputes-v1-0-api-openapi.yml
  format: yaml
  label: Qualpay Disputes v1.0 API
  slug: qualpay-disputes-v1-0-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-disputes-v1-0-api-openapi.yml
- filename: qualpay-embedded-fields-api-openapi.yml
  format: yaml
  label: Qualpay Embedded Fields API
  slug: qualpay-embedded-fields-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-embedded-fields-api-openapi.yml
- filename: qualpay-integrator-api-openapi.yml
  format: yaml
  label: Qualpay Integrator API
  slug: qualpay-integrator-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-integrator-api-openapi.yml
- filename: qualpay-invoicing-api-openapi.yml
  format: yaml
  label: Qualpay Invoicing API
  slug: qualpay-invoicing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-invoicing-api-openapi.yml
- filename: qualpay-payee-vault-api-openapi.yml
  format: yaml
  label: Qualpay Payee Vault API
  slug: qualpay-payee-vault-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-payee-vault-api-openapi.yml
- filename: qualpay-payment-gateway-api-openapi.yml
  format: yaml
  label: Qualpay Payment Gateway API
  slug: qualpay-payment-gateway-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-payment-gateway-api-openapi.yml
- filename: qualpay-recurring-billing-api-openapi.yml
  format: yaml
  label: Qualpay Recurring Billing API
  slug: qualpay-recurring-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-recurring-billing-api-openapi.yml
- filename: qualpay-reporting-api-openapi.yml
  format: yaml
  label: Qualpay Reporting API
  slug: qualpay-reporting-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-reporting-api-openapi.yml
- filename: qualpay-token-api-openapi.yml
  format: yaml
  label: Qualpay Token API
  slug: qualpay-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-token-api-openapi.yml
- filename: qualpay-transaction-api-openapi.yml
  format: yaml
  label: Qualpay Transaction API
  slug: qualpay-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-transaction-api-openapi.yml
- filename: qualpay-webhooks-api-openapi.yml
  format: yaml
  label: Qualpay Webhooks API
  slug: qualpay-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/qualpay/openapi/qualpay-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you represent a business, you are representing that you have the authority to bind the business to these terms.
    type: business
  minimum_age:
    text: You may not use the Services if you are under the age of eighteen (18).
    value: '18'
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
name: Qualpay
provenance_date: '2026-11-10'
provider_name: Qualpay
provider_slug: qualpay
slug: qualpay-eligibility
source_date: '2026-11-10'
source_filename: qualpay-eligibility.yml
source_heading: Eligibility
source_page: https://www.qualpay.com/legal/terms-and-conditions-v2
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qualpay\naid: qualpay\nurl: https://www.qualpay.com/legal/terms-and-conditions-v2\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you represent a business, you are representing that you have the authority to bind the business to these\n    terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not use the Services if you are under the age of eighteen (18).\n"
source_yaml_url: https://artifacts.apis.io/qualpay/eligibility/qualpay-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Qualpay's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Processing
- Merchant Services
- B2B Payments
- Reporting
- Tokenization
---
