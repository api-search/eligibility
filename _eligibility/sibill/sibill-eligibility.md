---
api_specs:
- filename: sibill-account-api-openapi.yml
  format: yaml
  label: Sibill Account API
  slug: sibill-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-account-api-openapi.yml
- filename: sibill-category-api-openapi.yml
  format: yaml
  label: Sibill Category API
  slug: sibill-category-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-category-api-openapi.yml
- filename: sibill-company-api-openapi.yml
  format: yaml
  label: Sibill Company API
  slug: sibill-company-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-company-api-openapi.yml
- filename: sibill-counterpart-api-openapi.yml
  format: yaml
  label: Sibill Counterpart API
  slug: sibill-counterpart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-counterpart-api-openapi.yml
- filename: sibill-document-api-openapi.yml
  format: yaml
  label: Sibill Document API
  slug: sibill-document-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-document-api-openapi.yml
- filename: sibill-documentsectional-api-openapi.yml
  format: yaml
  label: Sibill DocumentSectional API
  slug: sibill-documentsectional-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-documentsectional-api-openapi.yml
- filename: sibill-flow-api-openapi.yml
  format: yaml
  label: Sibill Flow API
  slug: sibill-flow-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-flow-api-openapi.yml
- filename: sibill-payment-api-openapi.yml
  format: yaml
  label: Sibill Payment API
  slug: sibill-payment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-payment-api-openapi.yml
- filename: sibill-product-api-openapi.yml
  format: yaml
  label: Sibill Product API
  slug: sibill-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-product-api-openapi.yml
- filename: sibill-reconciliation-api-openapi.yml
  format: yaml
  label: Sibill Reconciliation API
  slug: sibill-reconciliation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-reconciliation-api-openapi.yml
- filename: sibill-subcategory-api-openapi.yml
  format: yaml
  label: Sibill Subcategory API
  slug: sibill-subcategory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-subcategory-api-openapi.yml
- filename: sibill-transaction-api-openapi.yml
  format: yaml
  label: Sibill Transaction API
  slug: sibill-transaction-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sibill/openapi/sibill-transaction-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: indica la persona giuridica o la persona fisica che
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Consumers excluded
    text: i Servizi sono prestati esclusivamente a favore di Clienti che non siano qualificabili quali consumatori
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: dopo che Sibill ha validato l’idoneità di tale soggetto a usufruire dei Servizi
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Sibill
provenance_date: '2026-11-10'
provider_name: Sibill
provider_slug: sibill
slug: sibill-eligibility
source_date: '2026-11-10'
source_filename: sibill-eligibility.yml
source_heading: Eligibility
source_page: https://sibill.com/termini-e-condizioni/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sibill\naid: sibill\nurl: https://sibill.com/termini-e-condizioni/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: indica la persona giuridica o la persona fisica che\nrestricted_uses:\n- summary: Consumers excluded\n  text: i Servizi sono prestati esclusivamente a favore di Clienti che non siano qualificabili quali consumatori\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: dopo che Sibill ha validato l’idoneità di tale soggetto a usufruire dei Servizi\nminimum_age:\n  value: null\n  text:\
  \ null\n"
source_yaml_url: https://artifacts.apis.io/sibill/eligibility/sibill-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Sibill's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Invoicing
- Payments
- Reconciliation
- Accounting
- Banking
- Small Business
- Open Banking
- E-Invoicing
- Italy
---
