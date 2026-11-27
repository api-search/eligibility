---
api_specs:
- filename: staples-account-api-openapi.yml
  format: yaml
  label: Staples Account API
  slug: staples-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/staples/openapi/staples-account-api-openapi.yml
- filename: staples-catalog-api-openapi.yml
  format: yaml
  label: Staples Catalog API
  slug: staples-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/staples/openapi/staples-catalog-api-openapi.yml
- filename: staples-delivery-api-openapi.yml
  format: yaml
  label: Staples Delivery API
  slug: staples-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/staples/openapi/staples-delivery-api-openapi.yml
- filename: staples-invoices-api-openapi.yml
  format: yaml
  label: Staples Invoices API
  slug: staples-invoices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/staples/openapi/staples-invoices-api-openapi.yml
- filename: staples-orders-api-openapi.yml
  format: yaml
  label: Staples Orders API
  slug: staples-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/staples/openapi/staples-orders-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This website is intended for personal use by US residents only.
  entity_types:
  - text: This website is intended for personal use by US residents only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: personal use only
    text: This website is intended for personal use by US residents only.
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
name: Staples
provenance_date: '2026-11-10'
provider_name: Staples
provider_slug: staples
slug: staples-eligibility
source_date: '2026-11-10'
source_filename: staples-eligibility.yml
source_heading: Eligibility
source_page: https://www.staples.com/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Staples\naid: staples\nurl: https://www.staples.com/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This website is intended for personal use by US residents only.\nentity_types:\n- type: individual\n  text: This website is intended for personal use by US residents only.\nrestricted_uses:\n- summary: personal use only\n  text: This website is intended for personal use by US residents only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/staples/eligibility/staples-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Staples's own page on 2026-11-10.
synthetic: false
tags:
- Office Supplies
- Retail
- Procurement
- B2B
- eProcurement
- Fortune 500
---
