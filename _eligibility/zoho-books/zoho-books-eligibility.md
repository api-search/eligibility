---
api_specs:
- filename: zoho-books-contacts-api-openapi.yml
  format: yaml
  label: Zoho Books Contacts API
  slug: zoho-books-contacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoho-books/openapi/zoho-books-contacts-api-openapi.yml
- filename: zoho-books-invoices-api-openapi.yml
  format: yaml
  label: Zoho Books Invoices API
  slug: zoho-books-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoho-books/openapi/zoho-books-invoices-api-openapi.yml
- filename: zoho-books-items-api-openapi.yml
  format: yaml
  label: Zoho Books Items API
  slug: zoho-books-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoho-books/openapi/zoho-books-items-api-openapi.yml
- filename: zoho-books-organizations-api-openapi.yml
  format: yaml
  label: Zoho Books Organizations API
  slug: zoho-books-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/zoho-books/openapi/zoho-books-organizations-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: We provide cloud software and applications for businesses
    type: business
  minimum_age:
    text: You must be of legal age to enter into a binding agreement in order to accept the Agreement.
    value: null
  restricted_uses:
  - summary: No unauthorized third-party transfer
    text: transfer the Services or otherwise make it available to any third party
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
name: Zoho Books
provenance_date: '2026-11-10'
provider_name: Zoho Books
provider_slug: zoho-books
slug: zoho-books-eligibility
source_date: '2026-11-10'
source_filename: zoho-books-eligibility.yml
source_heading: Eligibility
source_page: https://www.zoho.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Zoho Books\naid: zoho-books\nurl: https://www.zoho.com/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: We provide cloud software and applications for businesses\nrestricted_uses:\n- summary: No unauthorized third-party transfer\n  text: transfer the Services or otherwise make it available to any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be of legal age to enter into a binding agreement in order to accept the Agreement.\n"
source_yaml_url: https://artifacts.apis.io/zoho-books/eligibility/zoho-books-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Zoho Books's own page on 2026-11-10.
synthetic: false
tags:
- Accounting
- Bookkeeping
- Invoicing
- Expenses
- Banking
- Small Business
- GST
- VAT
- Zoho
---
