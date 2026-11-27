---
api_specs:
- filename: ottimate-accounts-api-openapi.yml
  format: yaml
  label: Ottimate Accounts API
  slug: ottimate-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ottimate/openapi/ottimate-accounts-api-openapi.yml
- filename: ottimate-batch-api-openapi.yml
  format: yaml
  label: Ottimate Batch API
  slug: ottimate-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ottimate/openapi/ottimate-batch-api-openapi.yml
- filename: ottimate-catalog-api-openapi.yml
  format: yaml
  label: Ottimate Catalog API
  slug: ottimate-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ottimate/openapi/ottimate-catalog-api-openapi.yml
- filename: ottimate-dimensions-api-openapi.yml
  format: yaml
  label: Ottimate Dimensions API
  slug: ottimate-dimensions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ottimate/openapi/ottimate-dimensions-api-openapi.yml
- filename: ottimate-invoices-api-openapi.yml
  format: yaml
  label: Ottimate Invoices API
  slug: ottimate-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ottimate/openapi/ottimate-invoices-api-openapi.yml
- filename: ottimate-oauth-api-openapi.yml
  format: yaml
  label: Ottimate OAuth API
  slug: ottimate-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ottimate/openapi/ottimate-oauth-api-openapi.yml
- filename: ottimate-receipts-api-openapi.yml
  format: yaml
  label: Ottimate Receipts API
  slug: ottimate-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ottimate/openapi/ottimate-receipts-api-openapi.yml
- filename: ottimate-vendors-api-openapi.yml
  format: yaml
  label: Ottimate Vendors API
  slug: ottimate-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ottimate/openapi/ottimate-vendors-api-openapi.yml
- filename: ottimate-purchase-orders-api-openapi.yml
  format: yaml
  label: Ottimate Purchase Orders API
  slug: ottimate-purchase-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ottimate/openapi/ottimate-purchase-orders-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or fraudulent content
    text: Illegal, obscene, fraudulent, or pornographic Content; commercial solicitations of any kind
  - summary: PHI limits for HIPAA customers
    text: Customer agrees to only upload or transmit to Ottimate the minimum necessary amount of Protected Health Information (“PHI”) reasonably required for Ottimate’s provision of the Services.
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
name: Ottimate
provenance_date: '2026-11-10'
provider_name: Ottimate
provider_slug: ottimate
slug: ottimate-eligibility
source_date: '2026-11-10'
source_filename: ottimate-eligibility.yml
source_heading: Eligibility
source_page: https://ottimate.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ottimate\naid: ottimate\nurl: https://ottimate.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal or fraudulent content\n  text: Illegal, obscene, fraudulent, or pornographic Content; commercial solicitations of any kind\n- summary: PHI limits for HIPAA customers\n  text: Customer agrees to only upload or transmit to Ottimate the minimum necessary amount of Protected Health\n    Information (“PHI”) reasonably required for Ottimate’s provision of the Services.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ottimate/eligibility/ottimate-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Ottimate's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Enterprise Saas
- Accounts Payable
- Invoice Automation
- Payments
- Fintech
- Restaurant
- Procurement
- Spend Management
- ERP Integration
---
