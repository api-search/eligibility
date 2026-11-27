---
api_specs:
- filename: ordogrid-clients-api-openapi.yml
  format: yaml
  label: OrdoGrid Clients API
  slug: ordogrid-clients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-clients-api-openapi.yml
- filename: ordogrid-credit-notes-api-openapi.yml
  format: yaml
  label: OrdoGrid Credit Notes API
  slug: ordogrid-credit-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-credit-notes-api-openapi.yml
- filename: ordogrid-fidelity-api-openapi.yml
  format: yaml
  label: OrdoGrid Fidelity API
  slug: ordogrid-fidelity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-fidelity-api-openapi.yml
- filename: ordogrid-invoices-api-openapi.yml
  format: yaml
  label: OrdoGrid Invoices API
  slug: ordogrid-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-invoices-api-openapi.yml
- filename: ordogrid-meta-api-openapi.yml
  format: yaml
  label: OrdoGrid Meta API
  slug: ordogrid-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-meta-api-openapi.yml
- filename: ordogrid-payments-api-openapi.yml
  format: yaml
  label: OrdoGrid Payments API
  slug: ordogrid-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-payments-api-openapi.yml
- filename: ordogrid-peppol-api-openapi.yml
  format: yaml
  label: OrdoGrid Peppol API
  slug: ordogrid-peppol-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-peppol-api-openapi.yml
- filename: ordogrid-quotes-api-openapi.yml
  format: yaml
  label: OrdoGrid Quotes API
  slug: ordogrid-quotes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-quotes-api-openapi.yml
- filename: ordogrid-receipts-api-openapi.yml
  format: yaml
  label: OrdoGrid Receipts API
  slug: ordogrid-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ordogrid/openapi/ordogrid-receipts-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Platform is intended for professional use (B2B).
    type: business
  minimum_age:
    text: Be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Fraudulent or illegal use
    text: Not use the Platform for fraudulent or illegal purposes
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
name: OrdoGrid
provenance_date: '2026-11-10'
provider_name: OrdoGrid
provider_slug: ordogrid
slug: ordogrid-eligibility
source_date: '2026-11-10'
source_filename: ordogrid-eligibility.yml
source_heading: Eligibility
source_page: https://ordogrid.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OrdoGrid\naid: ordogrid\nurl: https://ordogrid.com/en/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Platform is intended for professional use (B2B).\nrestricted_uses:\n- summary: Fraudulent or illegal use\n  text: Not use the Platform for fraudulent or illegal purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/ordogrid/eligibility/ordogrid-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from OrdoGrid's own page on 2026-11-10.
synthetic: false
tags:
- Invoicing
- Peppol
- Belgium
- Software-as-a-Service
- business-documents
---
