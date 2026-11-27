---
api_specs:
- filename: spare-account-api-openapi.yml
  format: yaml
  label: Spare Account API
  slug: spare-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-account-api-openapi.yml
- filename: spare-accountinformationreport-api-openapi.yml
  format: yaml
  label: Spare AccountInformationReport API
  slug: spare-accountinformationreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-accountinformationreport-api-openapi.yml
- filename: spare-balance-api-openapi.yml
  format: yaml
  label: Spare Balance API
  slug: spare-balance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-balance-api-openapi.yml
- filename: spare-beneficiary-api-openapi.yml
  format: yaml
  label: Spare Beneficiary API
  slug: spare-beneficiary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-beneficiary-api-openapi.yml
- filename: spare-cert-api-openapi.yml
  format: yaml
  label: Spare Cert API
  slug: spare-cert-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-cert-api-openapi.yml
- filename: spare-connection-api-openapi.yml
  format: yaml
  label: Spare Connection API
  slug: spare-connection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-connection-api-openapi.yml
- filename: spare-consent-api-openapi.yml
  format: yaml
  label: Spare Consent API
  slug: spare-consent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-consent-api-openapi.yml
- filename: spare-customer-api-openapi.yml
  format: yaml
  label: Spare Customer API
  slug: spare-customer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-customer-api-openapi.yml
- filename: spare-parties-api-openapi.yml
  format: yaml
  label: Spare Parties API
  slug: spare-parties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-parties-api-openapi.yml
- filename: spare-payment-api-openapi.yml
  format: yaml
  label: Spare Payment API
  slug: spare-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-payment-api-openapi.yml
- filename: spare-provider-api-openapi.yml
  format: yaml
  label: Spare Provider API
  slug: spare-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-provider-api-openapi.yml
- filename: spare-request-api-openapi.yml
  format: yaml
  label: Spare Request API
  slug: spare-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-request-api-openapi.yml
- filename: spare-riskreport-api-openapi.yml
  format: yaml
  label: Spare RiskReport API
  slug: spare-riskreport-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-riskreport-api-openapi.yml
- filename: spare-statement-api-openapi.yml
  format: yaml
  label: Spare Statement API
  slug: spare-statement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-statement-api-openapi.yml
- filename: spare-token-api-openapi.yml
  format: yaml
  label: Spare Token API
  slug: spare-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-token-api-openapi.yml
- filename: spare-transaction-api-openapi.yml
  format: yaml
  label: Spare Transaction API
  slug: spare-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-transaction-api-openapi.yml
- filename: spare-direct-debit-api-openapi.yml
  format: yaml
  label: Spare Direct Debit API
  slug: spare-direct-debit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/spare/openapi/spare-direct-debit-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - SA
    - BH
    - AE
    text: Bahrain Kingdom of Saudi Arabia United Arab Emirates
  entity_types:
  - text: 'You may use the Services only if you: (i) are 18 years or older and capable of forming a binding contract with Spare'
    type: individual
  minimum_age:
    text: 'You may use the Services only if you: (i) are 18 years or older'
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You are only entitled to access and use the Services for lawful purposes.
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
name: Spare
provenance_date: '2026-11-10'
provider_name: Spare
provider_slug: spare
slug: spare-eligibility
source_date: '2026-11-10'
source_filename: spare-eligibility.yml
source_heading: Eligibility
source_page: https://terms.tryspare.com/sa/en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spare\naid: spare\nurl: https://terms.tryspare.com/sa/en\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SA\n  - BH\n  - AE\n  excluded: []\n  text: Bahrain Kingdom of Saudi Arabia United Arab Emirates\nentity_types:\n- type: individual\n  text: 'You may use the Services only if you: (i) are 18 years or older and capable of forming a binding contract\n    with Spare'\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You are only entitled to access and use the Services for lawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '18'\n  text: 'You may use the Services only if you: (i) are 18 years or older'\n"
source_yaml_url: https://artifacts.apis.io/spare/eligibility/spare-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Spare's own page on 2026-11-10.
synthetic: false
tags:
- Open Banking
- Open Finance
- Account Information
- Payment Initiation
- AISP
- PISP
- Consent
- Bank Data
- Transaction
- Balances
- Payments
- Fintech
- MENA
- Saudi Arabia
- Bahrain
- United Arab Emirates
---
