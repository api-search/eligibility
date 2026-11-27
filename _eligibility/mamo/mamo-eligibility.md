---
api_specs:
- filename: mamo-business-details-api-openapi.yml
  format: yaml
  label: Mamo Business Details API
  slug: mamo-business-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-business-details-api-openapi.yml
- filename: mamo-cards-api-openapi.yml
  format: yaml
  label: Mamo Cards API
  slug: mamo-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-cards-api-openapi.yml
- filename: mamo-expenses-api-openapi.yml
  format: yaml
  label: Mamo Expenses API
  slug: mamo-expenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-expenses-api-openapi.yml
- filename: mamo-getting-started-api-openapi.yml
  format: yaml
  label: Mamo Getting Started API
  slug: mamo-getting-started-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-getting-started-api-openapi.yml
- filename: mamo-invoices-api-openapi.yml
  format: yaml
  label: Mamo Invoices API
  slug: mamo-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-invoices-api-openapi.yml
- filename: mamo-payment-links-api-openapi.yml
  format: yaml
  label: Mamo Payment Links API
  slug: mamo-payment-links-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-payment-links-api-openapi.yml
- filename: mamo-payouts-api-openapi.yml
  format: yaml
  label: Mamo Payouts API
  slug: mamo-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-payouts-api-openapi.yml
- filename: mamo-receipts-api-openapi.yml
  format: yaml
  label: Mamo Receipts API
  slug: mamo-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-receipts-api-openapi.yml
- filename: mamo-recipients-api-openapi.yml
  format: yaml
  label: Mamo Recipients API
  slug: mamo-recipients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-recipients-api-openapi.yml
- filename: mamo-subscriptions-api-openapi.yml
  format: yaml
  label: Mamo Subscriptions API
  slug: mamo-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-subscriptions-api-openapi.yml
- filename: mamo-transactions-api-openapi.yml
  format: yaml
  label: Mamo Transactions API
  slug: mamo-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-transactions-api-openapi.yml
- filename: mamo-webhooks-api-openapi.yml
  format: yaml
  label: Mamo Webhooks API
  slug: mamo-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mamo/openapi/mamo-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AE
    text: These services and terms are for businesses in the UAE selling goods and services to customers.
  entity_types:
  - text: These services and terms are for businesses in the UAE selling goods and services to customers.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Restricted Business category
    text: If a Business engages or will engage in a “Restricted Business” (as defined below), it will be classified as a Restricted Business for the purposes of this agreement
  - summary: Prohibited Business category
    text: 'A business which is involved in one or more of the following activities (and this list of activities, or any part thereof, is subject to change by Mamo at any time and without notice): (a) cryptocurrency trading platforms;'
  verification:
    approval_required: true
    kyb: true
    kyc: true
    text: To receive the Services, the Business must complete Mamo’s onboarding process, including the Application Form, and pass Mamo’s prevailing “know your customer” checks and other checks and processes in place, and must be approved by Mamo
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mamo
provenance_date: '2026-11-10'
provider_name: Mamo
provider_slug: mamo
slug: mamo-eligibility
source_date: '2026-11-10'
source_filename: mamo-eligibility.yml
source_heading: Eligibility
source_page: https://www.mamopay.com/legal/terms-business
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mamo\naid: mamo\nurl: https://www.mamopay.com/legal/terms-business\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AE\n  excluded: []\n  text: These services and terms are for businesses in the UAE selling goods and services to customers.\nentity_types:\n- type: business\n  text: These services and terms are for businesses in the UAE selling goods and services to customers.\nrestricted_uses:\n- summary: Restricted Business category\n  text: If a Business engages or will engage in a “Restricted Business” (as defined below), it will be classified\n    as a Restricted Business for the purposes\
  \ of this agreement\n- summary: Prohibited Business category\n  text: 'A business which is involved in one or more of the following activities (and this list of activities, or\n    any part thereof, is subject to change by Mamo at any time and without notice): (a) cryptocurrency trading platforms;'\nverification:\n  kyc: true\n  kyb: true\n  approval_required: true\n  text: To receive the Services, the Business must complete Mamo’s onboarding process, including the Application\n    Form, and pass Mamo’s prevailing “know your customer” checks and other checks and processes in place, and must\n    be approved by Mamo\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mamo/eligibility/mamo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Mamo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Fintech
- Payment Links
- Subscription
- Corporate Cards
- Payouts
- Expense Management
- United Arab Emirates
- Middle East
- MENA
---
