---
api_specs:
- filename: workist-delivery-notes-api-openapi.yml
  format: yaml
  label: Workist Delivery Notes API
  slug: workist-delivery-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-delivery-notes-api-openapi.yml
- filename: workist-invoices-api-openapi.yml
  format: yaml
  label: Workist Invoices API
  slug: workist-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-invoices-api-openapi.yml
- filename: workist-list-of-services-api-openapi.yml
  format: yaml
  label: Workist List Of Services API
  slug: workist-list-of-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-list-of-services-api-openapi.yml
- filename: workist-master-data-api-openapi.yml
  format: yaml
  label: Workist Master Data API
  slug: workist-master-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-master-data-api-openapi.yml
- filename: workist-order-confirmations-api-openapi.yml
  format: yaml
  label: Workist Order Confirmations API
  slug: workist-order-confirmations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-order-confirmations-api-openapi.yml
- filename: workist-orders-api-openapi.yml
  format: yaml
  label: Workist Orders API
  slug: workist-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-orders-api-openapi.yml
- filename: workist-property-bills-api-openapi.yml
  format: yaml
  label: Workist Property Bills API
  slug: workist-property-bills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-property-bills-api-openapi.yml
- filename: workist-rfq-api-openapi.yml
  format: yaml
  label: Workist Rfq API
  slug: workist-rfq-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/workist/openapi/workist-rfq-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The services offered by Workist are intended exclusively for entrepreneurs within the meaning of Sec. 14 BGB.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Workist reserves the right to ask for appropriate information and to demand proof that the Customer is not a consumer according to Sec. 13 BGB (German Civil Code).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Workist
provenance_date: '2026-11-10'
provider_name: Workist
provider_slug: workist
slug: workist-eligibility
source_date: '2026-11-10'
source_filename: workist-eligibility.yml
source_heading: Eligibility
source_page: https://www.workist.com/en/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Workist\naid: workist\nurl: https://www.workist.com/en/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The services offered by Workist are intended exclusively for entrepreneurs within the meaning of Sec. 14\n    BGB.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Workist reserves the right to ask for appropriate information and to demand proof that the Customer is not\n    a consumer according to Sec. 13 BGB (German Civil Code).\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/workist/eligibility/workist-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Workist's own page on 2026-11-10.
synthetic: false
tags:
- Documents
- Document Processing
- Artificial Intelligence
- Automation
- Order
- Invoices
- ERP
- B2B
- Master Data
---
