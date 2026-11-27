---
api_specs:
- filename: allica-bank-account-access-api-openapi.yml
  format: yaml
  label: Allica Bank Account Access API
  slug: allica-bank-account-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-account-access-api-openapi.yml
- filename: allica-bank-accounts-api-openapi.yml
  format: yaml
  label: Allica Bank Accounts API
  slug: allica-bank-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-accounts-api-openapi.yml
- filename: allica-bank-balances-api-openapi.yml
  format: yaml
  label: Allica Bank Balances API
  slug: allica-bank-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-balances-api-openapi.yml
- filename: allica-bank-beneficiaries-api-openapi.yml
  format: yaml
  label: Allica Bank Beneficiaries API
  slug: allica-bank-beneficiaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-beneficiaries-api-openapi.yml
- filename: allica-bank-direct-debits-api-openapi.yml
  format: yaml
  label: Allica Bank Direct Debits API
  slug: allica-bank-direct-debits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-direct-debits-api-openapi.yml
- filename: allica-bank-domestic-payments-api-openapi.yml
  format: yaml
  label: Allica Bank Domestic Payments API
  slug: allica-bank-domestic-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-domestic-payments-api-openapi.yml
- filename: allica-bank-domestic-scheduled-payments-api-openapi.yml
  format: yaml
  label: Allica Bank Domestic Scheduled Payments API
  slug: allica-bank-domestic-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-domestic-scheduled-payments-api-openapi.yml
- filename: allica-bank-domestic-standing-orders-api-openapi.yml
  format: yaml
  label: Allica Bank Domestic Standing Orders API
  slug: allica-bank-domestic-standing-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-domestic-standing-orders-api-openapi.yml
- filename: allica-bank-file-payments-api-openapi.yml
  format: yaml
  label: Allica Bank File Payments API
  slug: allica-bank-file-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-file-payments-api-openapi.yml
- filename: allica-bank-offers-api-openapi.yml
  format: yaml
  label: Allica Bank Offers API
  slug: allica-bank-offers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-offers-api-openapi.yml
- filename: allica-bank-parties-api-openapi.yml
  format: yaml
  label: Allica Bank Parties API
  slug: allica-bank-parties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-parties-api-openapi.yml
- filename: allica-bank-payment-details-api-openapi.yml
  format: yaml
  label: Allica Bank Payment Details API
  slug: allica-bank-payment-details-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-payment-details-api-openapi.yml
- filename: allica-bank-products-api-openapi.yml
  format: yaml
  label: Allica Bank Products API
  slug: allica-bank-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-products-api-openapi.yml
- filename: allica-bank-scheduled-payments-api-openapi.yml
  format: yaml
  label: Allica Bank Scheduled Payments API
  slug: allica-bank-scheduled-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-scheduled-payments-api-openapi.yml
- filename: allica-bank-standing-orders-api-openapi.yml
  format: yaml
  label: Allica Bank Standing Orders API
  slug: allica-bank-standing-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-standing-orders-api-openapi.yml
- filename: allica-bank-transactions-api-openapi.yml
  format: yaml
  label: Allica Bank Transactions API
  slug: allica-bank-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/allica-bank/openapi/allica-bank-transactions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: Our site is directed to people residing in the United Kingdom.
  entity_types:
  - text: 'If you are a consumer user: Please note that we only provide our site for domestic and private use.'
    type: individual
  - text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms that may apply to our site or any content on it.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use by consumers
    text: You agree not to use our site for any commercial or business purposes, and we have no liability to you for any loss of profit, loss of business, business interruption, or loss of business opportunity.
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
name: Allica Bank
provenance_date: '2026-11-09'
provider_name: Allica Bank
provider_slug: allica-bank
slug: allica-bank-eligibility
source_date: '2026-11-09'
source_filename: allica-bank-eligibility.yml
source_heading: Eligibility
source_page: https://www.allica.bank/website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Allica Bank\naid: allica-bank\nurl: https://www.allica.bank/website-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: Our site is directed to people residing in the United Kingdom.\nentity_types:\n- type: individual\n  text: 'If you are a consumer user: Please note that we only provide our site for domestic and private use.'\n- type: business\n  text: 'If you are a business user: We exclude all implied conditions, warranties, representations or other terms\n    that may apply to our site or any content on it.'\nrestricted_uses:\n- summary: No commercial use by consumers\n\
  \  text: You agree not to use our site for any commercial or business purposes, and we have no liability to you for\n    any loss of profit, loss of business, business interruption, or loss of business opportunity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/allica-bank/eligibility/allica-bank-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Allica Bank's own page on 2026-11-09.
synthetic: false
tags:
- Financial Services
- Banking
- Open Banking
- PSD2
- OBIE
- FAPI
- United Kingdom
- Payments
- Account Information
- Small Business
- Business Banking
- Fintech
---
