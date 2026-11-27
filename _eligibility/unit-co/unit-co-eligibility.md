---
api_specs:
- filename: unit-co-accounts-api-openapi.yml
  format: yaml
  label: Unit Accounts API
  slug: unit-co-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-accounts-api-openapi.yml
- filename: unit-co-api-tokens-api-openapi.yml
  format: yaml
  label: Unit API Tokens API
  slug: unit-co-api-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-api-tokens-api-openapi.yml
- filename: unit-co-applications-api-openapi.yml
  format: yaml
  label: Unit Applications API
  slug: unit-co-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-applications-api-openapi.yml
- filename: unit-co-authorizations-api-openapi.yml
  format: yaml
  label: Unit Authorizations API
  slug: unit-co-authorizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-authorizations-api-openapi.yml
- filename: unit-co-cards-api-openapi.yml
  format: yaml
  label: Unit Cards API
  slug: unit-co-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-cards-api-openapi.yml
- filename: unit-co-checks-api-openapi.yml
  format: yaml
  label: Unit Checks API
  slug: unit-co-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-checks-api-openapi.yml
- filename: unit-co-counterparties-api-openapi.yml
  format: yaml
  label: Unit Counterparties API
  slug: unit-co-counterparties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-counterparties-api-openapi.yml
- filename: unit-co-credit-and-repayments-api-openapi.yml
  format: yaml
  label: Unit Credit and Repayments API
  slug: unit-co-credit-and-repayments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-credit-and-repayments-api-openapi.yml
- filename: unit-co-customers-api-openapi.yml
  format: yaml
  label: Unit Customers API
  slug: unit-co-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-customers-api-openapi.yml
- filename: unit-co-events-api-openapi.yml
  format: yaml
  label: Unit Events API
  slug: unit-co-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-events-api-openapi.yml
- filename: unit-co-fees-and-rewards-api-openapi.yml
  format: yaml
  label: Unit Fees and Rewards API
  slug: unit-co-fees-and-rewards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-fees-and-rewards-api-openapi.yml
- filename: unit-co-payments-api-openapi.yml
  format: yaml
  label: Unit Payments API
  slug: unit-co-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-payments-api-openapi.yml
- filename: unit-co-risk-and-fraud-api-openapi.yml
  format: yaml
  label: Unit Risk and Fraud API
  slug: unit-co-risk-and-fraud-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-risk-and-fraud-api-openapi.yml
- filename: unit-co-statements-api-openapi.yml
  format: yaml
  label: Unit Statements API
  slug: unit-co-statements-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-statements-api-openapi.yml
- filename: unit-co-tax-forms-api-openapi.yml
  format: yaml
  label: Unit Tax Forms API
  slug: unit-co-tax-forms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-tax-forms-api-openapi.yml
- filename: unit-co-transactions-api-openapi.yml
  format: yaml
  label: Unit Transactions API
  slug: unit-co-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-transactions-api-openapi.yml
- filename: unit-co-webhooks-api-openapi.yml
  format: yaml
  label: Unit Webhooks API
  slug: unit-co-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/unit-co/openapi/unit-co-webhooks-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Unit is designed to be used within the United States.
  entity_types:
  - text: you must be of legal age to form a binding contract with Unit
    type: individual
  - text: current or prospective customers of Unit (collectively, “ Program Partners ”)
    type: business
  minimum_age:
    text: you must be of legal age to form a binding contract with Unit
    value: legal age
  restricted_uses:
  - summary: No protected health information
    text: You agree that you will not send or transmit any electronic “Protected Health Information” (“ ePHI ”, as defined in HIPAA) to Unit or otherwise in any manner through the Platform and Services.
  - summary: Sandbox dummy data only
    text: You may use the Sandbox with only artificial, fabricated, or “dummy” data
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
name: Unit
provenance_date: '2026-11-10'
provider_name: Unit
provider_slug: unit-co
slug: unit-co-eligibility
source_date: '2026-11-10'
source_filename: unit-co-eligibility.yml
source_heading: Eligibility
source_page: https://www.unit.co/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unit\naid: unit-co\nurl: https://www.unit.co/terms-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Unit is designed to be used within the United States.\nentity_types:\n- type: individual\n  text: you must be of legal age to form a binding contract with Unit\n- type: business\n  text: current or prospective customers of Unit (collectively, “ Program Partners ”)\nrestricted_uses:\n- summary: No protected health information\n  text: You agree that you will not send or transmit any electronic “Protected Health Information” (“ ePHI ”, as\n    defined in HIPAA) to Unit\
  \ or otherwise in any manner through the Platform and Services.\n- summary: Sandbox dummy data only\n  text: You may use the Sandbox with only artificial, fabricated, or “dummy” data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you must be of legal age to form a binding contract with Unit\n"
source_yaml_url: https://artifacts.apis.io/unit-co/eligibility/unit-co-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Unit's own page on 2026-11-10.
synthetic: false
tags:
- Fintech
- Banking as a Service
- Banking
- Payments
- Card Issuing
- ACH
- Lending
- JSON:API
- Embedded Finance
---
