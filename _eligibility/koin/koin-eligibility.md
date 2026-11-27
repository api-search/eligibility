---
api_specs:
- filename: koin-access-api-openapi.yml
  format: yaml
  label: Koin Access API
  slug: koin-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-access-api-openapi.yml
- filename: koin-account-take-over-services-api-openapi.yml
  format: yaml
  label: Koin Account Take Over Services API
  slug: koin-account-take-over-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-account-take-over-services-api-openapi.yml
- filename: koin-availability-services-api-openapi.yml
  format: yaml
  label: Koin Availability Services API
  slug: koin-availability-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-availability-services-api-openapi.yml
- filename: koin-communication-services-api-openapi.yml
  format: yaml
  label: Koin Communication Services API
  slug: koin-communication-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-communication-services-api-openapi.yml
- filename: koin-ecommerce-api-openapi.yml
  format: yaml
  label: Koin Ecommerce API
  slug: koin-ecommerce-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-ecommerce-api-openapi.yml
- filename: koin-notification-services-sales-api-openapi.yml
  format: yaml
  label: Koin Notification Services Sales API
  slug: koin-notification-services-sales-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-notification-services-sales-api-openapi.yml
- filename: koin-onboarding-services-api-openapi.yml
  format: yaml
  label: Koin Onboarding Services API
  slug: koin-onboarding-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-onboarding-services-api-openapi.yml
- filename: koin-payment-services-api-openapi.yml
  format: yaml
  label: Koin Payment Services API
  slug: koin-payment-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-payment-services-api-openapi.yml
- filename: koin-payout-services-api-openapi.yml
  format: yaml
  label: Koin Payout Services API
  slug: koin-payout-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-payout-services-api-openapi.yml
- filename: koin-recipient-services-account-api-openapi.yml
  format: yaml
  label: Koin Recipient Services Account API
  slug: koin-recipient-services-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-recipient-services-account-api-openapi.yml
- filename: koin-refund-services-api-openapi.yml
  format: yaml
  label: Koin Refund Services API
  slug: koin-refund-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-refund-services-api-openapi.yml
- filename: koin-support-services-api-openapi.yml
  format: yaml
  label: Koin Support Services API
  slug: koin-support-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-support-services-api-openapi.yml
- filename: koin-tokenize-services-api-openapi.yml
  format: yaml
  label: Koin Tokenize Services API
  slug: koin-tokenize-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-tokenize-services-api-openapi.yml
- filename: koin-payment-request-api-openapi.yml
  format: yaml
  label: Koin Payment Request API
  slug: koin-payment-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/koin/openapi/koin-payment-request-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - BR
    text: Ter um endereço de residência válido no Brasil
  entity_types:
  - text: Ser pessoa física - não aceitamos CNPJs, ok?
    type: individual
  minimum_age:
    text: Ter mais de 18 anos
    value: '18'
  restricted_uses:
  - summary: No use of third-party CPF
    text: Como o meio de pagamento Koin gera uma dívida em nome do portador do CPF, não podemos permitir o empréstimo ou uso de CPF de terceiros para compras que não sejam do próprio titular.
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
name: Koin
provenance_date: '2026-11-09'
provider_name: Koin
provider_slug: koin
slug: koin-eligibility
source_date: '2026-11-09'
source_filename: koin-eligibility.yml
source_heading: Eligibility
source_page: https://termos.koin.com.br/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Koin\naid: koin\nurl: https://termos.koin.com.br/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - BR\n  excluded: []\n  text: Ter um endereço de residência válido no Brasil\nentity_types:\n- type: individual\n  text: Ser pessoa física - não aceitamos CNPJs, ok?\nrestricted_uses:\n- summary: No use of third-party CPF\n  text: Como o meio de pagamento Koin gera uma dívida em nome do portador do CPF, não podemos permitir o empréstimo\n    ou uso de CPF de terceiros para compras que não sejam do próprio titular.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '18'\n  text: Ter mais de 18 anos\n"
source_yaml_url: https://artifacts.apis.io/koin/eligibility/koin-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Koin's own page on 2026-11-09.
synthetic: false
tags:
- Payments
- Fraud Prevention
- Buy Now Pay Later
- Pix
- E-Commerce
- Financial Services
- Brazil
- Latin America
- Checkout
- Company
---
