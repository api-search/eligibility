---
api_specs:
- filename: bit2me-account-api-openapi.yml
  format: yaml
  label: Bit2Me Account API
  slug: bit2me-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-account-api-openapi.yml
- filename: bit2me-account-deprecated-methods-api-openapi.yml
  format: yaml
  label: Bit2Me Account Deprecated Methods API
  slug: bit2me-account-deprecated-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-account-deprecated-methods-api-openapi.yml
- filename: bit2me-auth-api-openapi.yml
  format: yaml
  label: Bit2Me Auth API
  slug: bit2me-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-auth-api-openapi.yml
- filename: bit2me-blockchain-manager-api-openapi.yml
  format: yaml
  label: Bit2Me Blockchain Manager API
  slug: bit2me-blockchain-manager-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-blockchain-manager-api-openapi.yml
- filename: bit2me-brokerage-api-openapi.yml
  format: yaml
  label: Bit2Me Brokerage API
  slug: bit2me-brokerage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-brokerage-api-openapi.yml
- filename: bit2me-compliance-api-openapi.yml
  format: yaml
  label: Bit2Me Compliance API
  slug: bit2me-compliance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-compliance-api-openapi.yml
- filename: bit2me-currency-api-openapi.yml
  format: yaml
  label: Bit2Me Currency API
  slug: bit2me-currency-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-currency-api-openapi.yml
- filename: bit2me-earn-api-openapi.yml
  format: yaml
  label: Bit2Me Earn API
  slug: bit2me-earn-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-earn-api-openapi.yml
- filename: bit2me-loan-api-openapi.yml
  format: yaml
  label: Bit2Me Loan API
  slug: bit2me-loan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-loan-api-openapi.yml
- filename: bit2me-misc-api-openapi.yml
  format: yaml
  label: Bit2Me Misc API
  slug: bit2me-misc-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-misc-api-openapi.yml
- filename: bit2me-pay-api-openapi.yml
  format: yaml
  label: Bit2Me Pay API
  slug: bit2me-pay-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-pay-api-openapi.yml
- filename: bit2me-teller-api-openapi.yml
  format: yaml
  label: Bit2Me Teller API
  slug: bit2me-teller-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-teller-api-openapi.yml
- filename: bit2me-trading-api-openapi.yml
  format: yaml
  label: Bit2Me Trading API
  slug: bit2me-trading-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-trading-api-openapi.yml
- filename: bit2me-verifier-api-openapi.yml
  format: yaml
  label: Bit2Me Verifier API
  slug: bit2me-verifier-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-verifier-api-openapi.yml
- filename: bit2me-verifier-deprecated-methods-api-openapi.yml
  format: yaml
  label: Bit2Me Verifier Deprecated Methods API
  slug: bit2me-verifier-deprecated-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-verifier-deprecated-methods-api-openapi.yml
- filename: bit2me-wallet-api-openapi.yml
  format: yaml
  label: Bit2Me Wallet API
  slug: bit2me-wallet-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bit2me/openapi/bit2me-wallet-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    - AR
    text: For users residing in Brazil, Bit2Me only offers the Brazilian instant payment method - PIX. Any user residing in Argentina who intends to create an account and operate on Bit2Me must accept these terms and conditions
  entity_types:
  - text: Individuals of legal age with full capacity to contract, who subscribe to these GENERAL TERMS AND CONDITIONS
    type: individual
  - text: In cases where the user accesses the platform on behalf of a legal entity, the user accepts and declares that they have sufficient powers of representation to bind the legal entity or company they represent to the contracting of services.
    type: business
  minimum_age:
    text: Minors may not use the services that Bit2Me provides through the website or Application, so any application for membership in Bit2Me from a person under eighteen (18) years of age will be denied.
    value: '18'
  restricted_uses:
  - summary: Services may be restricted
    text: Bit2Me may limit and/or restrict certain services to users in accordance with applicable regulations and internal policies.
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
name: Bit2Me
provenance_date: '2026-11-09'
provider_name: Bit2Me
provider_slug: bit2me
slug: bit2me-eligibility
source_date: '2026-11-09'
source_filename: bit2me-eligibility.yml
source_heading: Eligibility
source_page: https://legal.bit2me.com/en/support/solutions/articles/35000292850-general-terms-and-conditions-for-bit2me-services
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bit2Me\naid: bit2me\nurl: https://legal.bit2me.com/en/support/solutions/articles/35000292850-general-terms-and-conditions-for-bit2me-services\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - BR\n  - AR\n  excluded: []\n  text: For users residing in Brazil, Bit2Me only offers the Brazilian instant payment method - PIX. Any user residing\n    in Argentina who intends to create an account and operate on Bit2Me must accept these terms and conditions\nentity_types:\n- type: individual\n  text: Individuals of legal age with full capacity to contract, who subscribe to these GENERAL TERMS AND\
  \ CONDITIONS\n- type: business\n  text: In cases where the user accesses the platform on behalf of a legal entity, the user accepts and declares\n    that they have sufficient powers of representation to bind the legal entity or company they represent to the\n    contracting of services.\nrestricted_uses:\n- summary: Services may be restricted\n  text: Bit2Me may limit and/or restrict certain services to users in accordance with applicable regulations and\n    internal policies.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Minors may not use the services that Bit2Me provides through the website or Application, so any application\n    for membership in Bit2Me from a person under eighteen (18) years of age will be denied.\n"
source_yaml_url: https://artifacts.apis.io/bit2me/eligibility/bit2me-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Bit2Me's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Fintech
- Exchange
- Payments
---
