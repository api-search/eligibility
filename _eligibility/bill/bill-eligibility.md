---
api_specs:
- filename: bill-webhooks-asyncapi.yml
  format: yaml
  label: BILL v3 API
  slug: v3-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/bill/asyncapi/bill-webhooks-asyncapi.yml
- filename: bill-authentication-api-openapi.yml
  format: yaml
  label: BILL Authentication API
  slug: bill-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-authentication-api-openapi.yml
- filename: bill-bills-api-openapi.yml
  format: yaml
  label: BILL Bills API
  slug: bill-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-bills-api-openapi.yml
- filename: bill-customers-api-openapi.yml
  format: yaml
  label: BILL Customers API
  slug: bill-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-customers-api-openapi.yml
- filename: bill-funding-accounts-api-openapi.yml
  format: yaml
  label: BILL Funding Accounts API
  slug: bill-funding-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-funding-accounts-api-openapi.yml
- filename: bill-invoices-api-openapi.yml
  format: yaml
  label: BILL Invoices API
  slug: bill-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-invoices-api-openapi.yml
- filename: bill-organizations-api-openapi.yml
  format: yaml
  label: BILL Organizations API
  slug: bill-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-organizations-api-openapi.yml
- filename: bill-payments-api-openapi.yml
  format: yaml
  label: BILL Payments API
  slug: bill-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-payments-api-openapi.yml
- filename: bill-vendors-api-openapi.yml
  format: yaml
  label: BILL Vendors API
  slug: bill-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-vendors-api-openapi.yml
- filename: bill-webhooks-api-openapi.yml
  format: yaml
  label: BILL Webhooks API
  slug: bill-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bill/openapi/bill-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - CA
    text: Users and Your Organization or Individual, as appropriate, reside in the United States (except if You have created a Canadian BILL account or an IBR account ...)
  minimum_age:
    text: all Users are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Sanctioned countries/persons
    text: You will not use the Service to send money, either directly or indirectly, to a sanctioned country, person, group or entity.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We, and banks that offer services through BILL, will ask You for Your name, address, date of birth, and if You are located within the United States, Your social security number (SSN) and/or Employer Identification Number (EIN)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: BILL
provenance_date: '2026-11-09'
provider_name: BILL
provider_slug: bill
slug: bill-eligibility
source_date: '2026-11-09'
source_filename: bill-eligibility.yml
source_heading: Eligibility
source_page: https://www.bill.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BILL\naid: bill\nurl: https://www.bill.com/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  - CA\n  excluded: []\n  text: Users and Your Organization or Individual, as appropriate, reside in the United States (except if You have\n    created a Canadian BILL account or an IBR account ...)\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned countries/persons\n  text: You will not use the Service to send money, either directly or indirectly, to a sanctioned country, person,\n    group or entity.\nverification:\n  kyc: true\n  kyb: null\n  approval_required:\
  \ null\n  text: We, and banks that offer services through BILL, will ask You for Your name, address, date of birth, and\n    if You are located within the United States, Your social security number (SSN) and/or Employer Identification\n    Number (EIN)\nminimum_age:\n  value: '18'\n  text: all Users are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/bill/eligibility/bill-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from BILL's own page on 2026-11-09.
synthetic: false
tags:
- Accounts Payable
- Accounts Receivable
- Spend Management
- Expense Management
- Payments
- Bill Pay
- Financial Operations
- Fintech
- Accounting
---
