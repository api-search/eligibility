---
api_specs:
- filename: trustly-accounts-api-openapi.yml
  format: yaml
  label: Trustly Group Accounts API
  slug: trustly-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-accounts-api-openapi.yml
- filename: trustly-api-api-openapi.yml
  format: yaml
  label: Trustly Group API
  slug: trustly-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-api-api-openapi.yml
- filename: trustly-countries-api-openapi.yml
  format: yaml
  label: Trustly Group Countries API
  slug: trustly-countries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-countries-api-openapi.yml
- filename: trustly-customers-api-openapi.yml
  format: yaml
  label: Trustly Group Customers API
  slug: trustly-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-customers-api-openapi.yml
- filename: trustly-identity-api-openapi.yml
  format: yaml
  label: Trustly Group Identity API
  slug: trustly-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-identity-api-openapi.yml
- filename: trustly-networkcheckapi-api-openapi.yml
  format: yaml
  label: Trustly Group Network Check API
  slug: trustly-networkcheckapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-networkcheckapi-api-openapi.yml
- filename: trustly-payments-api-openapi.yml
  format: yaml
  label: Trustly Group Payments API
  slug: trustly-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-payments-api-openapi.yml
- filename: trustly-transactions-api-openapi.yml
  format: yaml
  label: Trustly Group Transactions API
  slug: trustly-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-transactions-api-openapi.yml
- filename: trustly-verifycustomer-api-openapi.yml
  format: yaml
  label: Trustly Group Verify Customer API
  slug: trustly-verifycustomer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-verifycustomer-api-openapi.yml
- filename: trustly-account-data-api-openapi.yml
  format: yaml
  label: Trustly Group Account Data API
  slug: trustly-account-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-account-data-api-openapi.yml
- filename: trustly-dispute-management-api-openapi.yml
  format: yaml
  label: Trustly Group Dispute Management API
  slug: trustly-dispute-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-dispute-management-api-openapi.yml
- filename: trustly-payment-providers-api-openapi.yml
  format: yaml
  label: Trustly Group Payment Providers API
  slug: trustly-payment-providers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/trustly/openapi/trustly-payment-providers-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - SE
    - GB
    text: you have used our services in the UK, you may be able to refer your complaint to the UK Financial Ombudsman Service
  entity_types:
  - text: you, in the capacity of a natural person, wish to make a purchase from, authenticate yourself towards or share account information with, Trustly
    type: individual
  - text: will not use the Service in the capacity of a legal person or by using a corporate account
    type: business
  minimum_age:
    text: you must be of at least eighteen (18) years old, or of such age as required by the Supplier
    value: '18'
  restricted_uses:
  - summary: Fraudulent, unlawful or abusive use
    text: will not use the Service for any fraudulent, unlawful or abusive purpose
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: information may be requested from you in order to establish for instance your identity, purpose of the payment transaction and origin of funds
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Trustly Group
provenance_date: '2026-11-10'
provider_name: Trustly Group
provider_slug: trustly
slug: trustly-eligibility
source_date: '2026-11-10'
source_filename: trustly-eligibility.yml
source_heading: Eligibility
source_page: https://www.trustly.com/about-us/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trustly Group\naid: trustly\nurl: https://www.trustly.com/about-us/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SE\n  - GB\n  excluded: []\n  text: you have used our services in the UK, you may be able to refer your complaint to the UK Financial Ombudsman\n    Service\nentity_types:\n- type: individual\n  text: you, in the capacity of a natural person, wish to make a purchase from, authenticate yourself towards or\n    share account information with, Trustly\n- type: business\n  text: will not use the Service in the capacity of a legal person or by using a corporate account\nrestricted_uses:\n\
  - summary: Fraudulent, unlawful or abusive use\n  text: will not use the Service for any fraudulent, unlawful or abusive purpose\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: information may be requested from you in order to establish for instance your identity, purpose of the payment\n    transaction and origin of funds\nminimum_age:\n  value: '18'\n  text: you must be of at least eighteen (18) years old, or of such age as required by the Supplier\n"
source_yaml_url: https://artifacts.apis.io/trustly/eligibility/trustly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Trustly Group's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Pay by Bank
- Open Banking
- Account-to-Account
- Payouts
- Direct Debit
- Bank Account Verification
- Identity Verification
- Fintech
- Webhook
- MCP
---
