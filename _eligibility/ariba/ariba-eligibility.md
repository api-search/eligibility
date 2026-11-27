---
api_specs:
- filename: ariba-invoices-api-openapi.yml
  format: yaml
  label: Ariba Invoices API
  slug: ariba-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ariba/openapi/ariba-invoices-api-openapi.yml
- filename: ariba-purchase-order-line-items-api-openapi.yml
  format: yaml
  label: Ariba Purchase Order Line Items API
  slug: ariba-purchase-order-line-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ariba/openapi/ariba-purchase-order-line-items-api-openapi.yml
- filename: ariba-purchase-orders-api-openapi.yml
  format: yaml
  label: Ariba Purchase Orders API
  slug: ariba-purchase-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ariba/openapi/ariba-purchase-orders-api-openapi.yml
- filename: ariba-receipts-api-openapi.yml
  format: yaml
  label: Ariba Receipts API
  slug: ariba-receipts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ariba/openapi/ariba-receipts-api-openapi.yml
- filename: ariba-requisitions-api-openapi.yml
  format: yaml
  label: Ariba Requisitions API
  slug: ariba-requisitions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ariba/openapi/ariba-requisitions-api-openapi.yml
- filename: ariba-suppliers-api-openapi.yml
  format: yaml
  label: Ariba Suppliers API
  slug: ariba-suppliers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/ariba/openapi/ariba-suppliers-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The right to use the Portal is worldwide, with the exception of those countries listed
  entity_types:
  - text: only if the company you work for, or that you represent as a consultant, ("Your Company") is either a Buyer or Supplier user of the SAP Ariba Cloud Services (a "Customer") or Your Company has executed a Partner Program Agreement
    type: business
  minimum_age:
    text: null
    value: null
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
name: Ariba
provenance_date: '2026-11-09'
provider_name: Ariba
provider_slug: ariba
slug: ariba-eligibility
source_date: '2026-11-09'
source_filename: ariba-eligibility.yml
source_heading: Eligibility
source_page: https://developer.ariba.com/api/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ariba\naid: ariba\nurl: https://developer.ariba.com/api/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The right to use the Portal is worldwide, with the exception of those countries listed\nentity_types:\n- type: business\n  text: only if the company you work for, or that you represent as a consultant, (\"Your Company\") is either a Buyer\n    or Supplier user of the SAP Ariba Cloud Services (a \"Customer\") or Your Company has executed a Partner Program\n    Agreement\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/ariba/eligibility/ariba-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Ariba's own page on 2026-11-09.
synthetic: false
tags:
- B2B
- Catalog Management
- Compliance
- Contracts
- Enterprise
- Integration
- Invoicing
- Procurement
- Risk Management
- SAP
- Sourcing
- Spend Analysis
- Supplier Lifecycle
- Suppliers
- Supply Chain
---
