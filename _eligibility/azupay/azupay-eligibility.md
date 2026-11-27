---
api_specs:
- filename: azupay-api-keys-api-openapi.yml
  format: yaml
  label: Azupay API Keys API
  slug: azupay-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-api-keys-api-openapi.yml
- filename: azupay-billing-and-transaction-reports-api-openapi.yml
  format: yaml
  label: Azupay Billing and Transaction Reports API
  slug: azupay-billing-and-transaction-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-billing-and-transaction-reports-api-openapi.yml
- filename: azupay-check-accounts-api-openapi.yml
  format: yaml
  label: Azupay Check Accounts API
  slug: azupay-check-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-check-accounts-api-openapi.yml
- filename: azupay-clients-api-openapi.yml
  format: yaml
  label: Azupay Clients API
  slug: azupay-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-clients-api-openapi.yml
- filename: azupay-current-balances-api-openapi.yml
  format: yaml
  label: Azupay Current Balances API
  slug: azupay-current-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-current-balances-api-openapi.yml
- filename: azupay-payment-agreement-api-openapi.yml
  format: yaml
  label: Azupay Payment Agreement API
  slug: azupay-payment-agreement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-agreement-api-openapi.yml
- filename: azupay-payment-agreement-request-api-openapi.yml
  format: yaml
  label: Azupay Payment Agreement Request API
  slug: azupay-payment-agreement-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-agreement-request-api-openapi.yml
- filename: azupay-payment-api-openapi.yml
  format: yaml
  label: Azupay Payment API
  slug: azupay-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-api-openapi.yml
- filename: azupay-payment-initiation-api-openapi.yml
  format: yaml
  label: Azupay Payment Initiation API
  slug: azupay-payment-initiation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-initiation-api-openapi.yml
- filename: azupay-payment-request-api-openapi.yml
  format: yaml
  label: Azupay Payment Request API
  slug: azupay-payment-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/azupay/openapi/azupay-payment-request-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The page lists sanctioned countries that Azupay merchants may not conduct business with without prior written approval, but does not state which countries the service serves.
  minimum_age:
    text: You must be over 18 years of age to use this website and to purchase any goods or services.
    value: '18'
  restricted_uses:
  - summary: Sanctioned countries list
    text: The following is a non-exhaustive list of countries which Azupay merchants are sanctioned from conducting business dealings with without prior written approval.
  - summary: Competitors excluded
    text: If you are in the business of creating similar documents, goods or services for the purpose of providing them for a fee to users, whether they be business users or domestic users, then you are a competitor of Azupay.
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
name: Azupay
provenance_date: '2026-11-09'
provider_name: Azupay
provider_slug: azupay
slug: azupay-eligibility
source_date: '2026-11-09'
source_filename: azupay-eligibility.yml
source_heading: Eligibility
source_page: https://azupay.com.au/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Azupay\naid: azupay\nurl: https://azupay.com.au/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The page lists sanctioned countries that Azupay merchants may not conduct business with without prior written\n    approval, but does not state which countries the service serves.\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned countries list\n  text: The following is a non-exhaustive list of countries which Azupay merchants are sanctioned from conducting\n    business dealings with without prior written approval.\n- summary: Competitors excluded\n  text: If you are in\
  \ the business of creating similar documents, goods or services for the purpose of providing\n    them for a fee to users, whether they be business users or domestic users, then you are a competitor of Azupay.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be over 18 years of age to use this website and to purchase any goods or services.\n"
source_yaml_url: https://artifacts.apis.io/azupay/eligibility/azupay-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Azupay's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Australia
- Real-Time Payments
- Account-to-Account
- New Payments Platform
- PayID
- PayTo
- Money Transfer
- Confirmation of Payee
- Open Banking
---
