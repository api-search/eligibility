---
api_specs:
- filename: processout-balances-api-openapi.yml
  format: yaml
  label: ProcessOut Balances API
  slug: processout-balances-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-balances-api-openapi.yml
- filename: processout-cards-api-openapi.yml
  format: yaml
  label: ProcessOut Cards API
  slug: processout-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-cards-api-openapi.yml
- filename: processout-customers-api-openapi.yml
  format: yaml
  label: ProcessOut Customers API
  slug: processout-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-customers-api-openapi.yml
- filename: processout-events-api-openapi.yml
  format: yaml
  label: ProcessOut Events API
  slug: processout-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-events-api-openapi.yml
- filename: processout-invoices-api-openapi.yml
  format: yaml
  label: ProcessOut Invoices API
  slug: processout-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-invoices-api-openapi.yml
- filename: processout-network-tokens-api-openapi.yml
  format: yaml
  label: ProcessOut Network Tokens API
  slug: processout-network-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-network-tokens-api-openapi.yml
- filename: processout-payouts-api-openapi.yml
  format: yaml
  label: ProcessOut Payouts API
  slug: processout-payouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-payouts-api-openapi.yml
- filename: processout-projects-api-openapi.yml
  format: yaml
  label: ProcessOut Projects API
  slug: processout-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-projects-api-openapi.yml
- filename: processout-transactions-api-openapi.yml
  format: yaml
  label: ProcessOut Transactions API
  slug: processout-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-transactions-api-openapi.yml
- filename: processout-uploads-api-openapi.yml
  format: yaml
  label: ProcessOut Uploads API
  slug: processout-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/processout/openapi/processout-uploads-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: Customer is at least 18 years old and has the legal capacity to be bound by this Agreement
    value: '18'
  restricted_uses:
  - summary: Unlawful or infringing customer data
    text: None of the Customer Data (as defined herein) will contain any unlawful, defamatory, offensive, libelous, harassing, abusive, fraudulent, pornographic or obscene content or material
  - summary: Protected health information
    text: upload or otherwise make available to ProcessOut any Customer Data that constitutes protected health information subject to the Health Insurance Portability and Accountability Act
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer will provide ProcessOut with any information, records, or materials that we request to verify Customer’s compliance with the eligibility requirements set forth above
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ProcessOut
provenance_date: '2026-11-10'
provider_name: ProcessOut
provider_slug: processout
slug: processout-eligibility
source_date: '2026-11-10'
source_filename: processout-eligibility.yml
source_heading: Eligibility
source_page: https://www.processout.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ProcessOut\naid: processout\nurl: https://www.processout.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or infringing customer data\n  text: None of the Customer Data (as defined herein) will contain any unlawful, defamatory, offensive, libelous,\n    harassing, abusive, fraudulent, pornographic or obscene content or material\n- summary: Protected health information\n  text: upload or otherwise make available to ProcessOut any Customer Data that constitutes protected health information\n    subject\
  \ to the Health Insurance Portability and Accountability Act\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer will provide ProcessOut with any information, records, or materials that we request to verify Customer’s\n    compliance with the eligibility requirements set forth above\nminimum_age:\n  value: '18'\n  text: Customer is at least 18 years old and has the legal capacity to be bound by this Agreement\n"
source_yaml_url: https://artifacts.apis.io/processout/eligibility/processout-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from ProcessOut's own page on 2026-11-10.
synthetic: false
tags:
- Payments
- Payment Orchestration
- Smart Routing
- Tokenization
- Checkout
- Reconciliation
- Fraud Prevention
- 3D Secure
- Company
---
