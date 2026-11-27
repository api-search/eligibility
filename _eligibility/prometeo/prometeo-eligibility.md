---
api_specs:
- filename: prometeo-account-validation-api-openapi.yml
  format: yaml
  label: Prometeo Account Validation API
  slug: prometeo-account-validation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-account-validation-api-openapi.yml
- filename: prometeo-banking-api-openapi.yml
  format: yaml
  label: Prometeo Banking API
  slug: prometeo-banking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-banking-api-openapi.yml
- filename: prometeo-cross-border-api-openapi.yml
  format: yaml
  label: Prometeo Cross-Border API
  slug: prometeo-cross-border-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-cross-border-api-openapi.yml
- filename: prometeo-identity-api-openapi.yml
  format: yaml
  label: Prometeo Identity API
  slug: prometeo-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-identity-api-openapi.yml
- filename: prometeo-payment-api-openapi.yml
  format: yaml
  label: Prometeo Payment API
  slug: prometeo-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/prometeo/openapi/prometeo-payment-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Customer must be a legally registered entity in a supported country or territory
  entity_types:
  - text: Customer must be a legally registered entity in a supported country or territory and successfully complete our Know Your Customer (KYC) / Know Your Business (KYB) verification process.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Data services limited to payee validation
    text: The data services may be used solely for the purpose of validating bank account details of payees or beneficiaries in connection with payments or transfers to be made by the Customer.
  verification:
    approval_required: null
    kyb: true
    kyc: true
    text: Customer must be a legally registered entity in a supported country or territory and successfully complete our Know Your Customer (KYC) / Know Your Business (KYB) verification process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Prometeo
provenance_date: '2026-11-10'
provider_name: Prometeo
provider_slug: prometeo
slug: prometeo-eligibility
source_date: '2026-11-10'
source_filename: prometeo-eligibility.yml
source_heading: Eligibility
source_page: https://prometeoapi.com/en/legal/msa
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prometeo\naid: prometeo\nurl: https://prometeoapi.com/en/legal/msa\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Customer must be a legally registered entity in a supported country or territory\nentity_types:\n- type: business\n  text: Customer must be a legally registered entity in a supported country or territory and successfully complete\n    our Know Your Customer (KYC) / Know Your Business (KYB) verification process.\nrestricted_uses:\n- summary: Data services limited to payee validation\n  text: The data services may be used solely for the purpose of validating bank account\
  \ details of payees or beneficiaries\n    in connection with payments or transfers to be made by the Customer.\nverification:\n  kyc: true\n  kyb: true\n  approval_required: null\n  text: Customer must be a legally registered entity in a supported country or territory and successfully complete\n    our Know Your Customer (KYC) / Know Your Business (KYB) verification process.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prometeo/eligibility/prometeo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Prometeo's own page on 2026-11-10.
synthetic: false
tags:
- Open Banking
- Payments
- Fintech
- Latin America
- Financial Data
- Account Validation
- Cross-Border
---
