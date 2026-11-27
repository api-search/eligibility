---
api_specs:
- filename: uzum-api-mfo-api-openapi.yml
  format: yaml
  label: Uzum API MFO API
  slug: uzum-api-mfo-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-api-mfo-api-openapi.yml
- filename: uzum-auxiliary-methods-api-openapi.yml
  format: yaml
  label: Uzum Auxiliary Methods API
  slug: uzum-auxiliary-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-auxiliary-methods-api-openapi.yml
- filename: uzum-back-to-back-payment-api-openapi.yml
  format: yaml
  label: Uzum Back-to-back Payment API
  slug: uzum-back-to-back-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-back-to-back-payment-api-openapi.yml
- filename: uzum-check-service-status-api-openapi.yml
  format: yaml
  label: Uzum Check Service Status API
  slug: uzum-check-service-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-check-service-status-api-openapi.yml
- filename: uzum-common-methods-api-openapi.yml
  format: yaml
  label: Uzum Common methods API
  slug: uzum-common-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-common-methods-api-openapi.yml
- filename: uzum-cross-border-payments-api-openapi.yml
  format: yaml
  label: Uzum Cross-border payments API
  slug: uzum-cross-border-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-cross-border-payments-api-openapi.yml
- filename: uzum-fiscalization-api-openapi.yml
  format: yaml
  label: Uzum Fiscalization API
  slug: uzum-fiscalization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-fiscalization-api-openapi.yml
- filename: uzum-from-uzbekistan-api-openapi.yml
  format: yaml
  label: Uzum From Uzbekistan API
  slug: uzum-from-uzbekistan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-from-uzbekistan-api-openapi.yml
- filename: uzum-information-retrieval-api-openapi.yml
  format: yaml
  label: Uzum Information retrieval API
  slug: uzum-information-retrieval-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-information-retrieval-api-openapi.yml
- filename: uzum-managing-credit-cards-bindings-api-openapi.yml
  format: yaml
  label: Uzum Managing Credit Cards Bindings API
  slug: uzum-managing-credit-cards-bindings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-managing-credit-cards-bindings-api-openapi.yml
- filename: uzum-methods-api-openapi.yml
  format: yaml
  label: Uzum Methods API
  slug: uzum-methods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-methods-api-openapi.yml
- filename: uzum-one-step-payment-api-openapi.yml
  format: yaml
  label: Uzum One-Step Payment API
  slug: uzum-one-step-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-one-step-payment-api-openapi.yml
- filename: uzum-partner-api-openapi.yml
  format: yaml
  label: Uzum Partner API
  slug: uzum-partner-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-partner-api-openapi.yml
- filename: uzum-submit-qr-code-payment-receipt-to-tax-authorities-api-openapi.yml
  format: yaml
  label: Uzum Submit QR Code Payment Receipt to Tax Authorities API
  slug: uzum-submit-qr-code-payment-receipt-to-tax-authorities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-submit-qr-code-payment-receipt-to-tax-authorities-api-openapi.yml
- filename: uzum-to-uzbekistan-api-openapi.yml
  format: yaml
  label: Uzum To Uzbekistan API
  slug: uzum-to-uzbekistan-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-to-uzbekistan-api-openapi.yml
- filename: uzum-transfer-process-api-openapi.yml
  format: yaml
  label: Uzum Transfer process API
  slug: uzum-transfer-process-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-transfer-process-api-openapi.yml
- filename: uzum-two-step-payment-api-openapi.yml
  format: yaml
  label: Uzum Two-Step Payment API
  slug: uzum-two-step-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/uzum/openapi/uzum-two-step-payment-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'User: a legally competent individual who is at least 18 years of age and is applying for positions with the Operator.'
    type: individual
  minimum_age:
    text: a legally competent individual who is at least 18 years of age and is applying for positions with the Operator.
    value: '18'
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
name: Uzum
provenance_date: '2026-11-10'
provider_name: Uzum
provider_slug: uzum
slug: uzum-eligibility
source_date: '2026-11-10'
source_filename: uzum-eligibility.yml
source_heading: Eligibility
source_page: https://uzum.com/en/privacy-and-terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Uzum\naid: uzum\nurl: https://uzum.com/en/privacy-and-terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'User: a legally competent individual who is at least 18 years of age and is applying for positions with\n    the Operator.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: a legally competent individual who is at least 18 years of age and is applying for positions with the Operator.\n"
source_yaml_url: https://artifacts.apis.io/uzum/eligibility/uzum-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Uzum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Payments
- Banking
- Financial Services
- E-Commerce
- Marketplace
- Money Transfer
- Remittances
- Buy Now Pay Later
- Acquiring
- QR Payments
- Fiscalization
- Banking as a Service
- Uzbekistan
- Central Asia
---
