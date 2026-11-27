---
api_specs:
- filename: channable-order-attachments-api-openapi.yml
  format: yaml
  label: Channable Order Attachments API
  slug: channable-order-attachments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channable/openapi/channable-order-attachments-api-openapi.yml
- filename: channable-orders-api-openapi.yml
  format: yaml
  label: Channable Orders API
  slug: channable-orders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channable/openapi/channable-orders-api-openapi.yml
- filename: channable-returns-api-openapi.yml
  format: yaml
  label: Channable Returns API
  slug: channable-returns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channable/openapi/channable-returns-api-openapi.yml
- filename: channable-statistics-api-openapi.yml
  format: yaml
  label: Channable Statistics API
  slug: channable-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channable/openapi/channable-statistics-api-openapi.yml
- filename: channable-stock-updates-api-openapi.yml
  format: yaml
  label: Channable Stock Updates API
  slug: channable-stock-updates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channable/openapi/channable-stock-updates-api-openapi.yml
- filename: channable-transporters-api-openapi.yml
  format: yaml
  label: Channable Transporters API
  slug: channable-transporters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/channable/openapi/channable-transporters-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you subscribe to the Service on behalf of a business, you represent to Channable that you have the authority to bind that business
    type: business
  - text: Minors under the age of 13 are not permitted to use the Service.
    type: individual
  minimum_age:
    text: Minors under the age of 13 are not permitted to use the Service. If the laws of your country of residence so permit, minor children may utilize the Service, provided that their parent or legal guardian establishes the account
    value: '13'
  restricted_uses:
  - summary: Unlawful or harmful use
    text: You may not use the Service to disseminate any unlawful or other objectionable material, or to harm others or the Service itself.
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
name: Channable
provenance_date: '2026-11-09'
provider_name: Channable
provider_slug: channable
slug: channable-eligibility
source_date: '2026-11-09'
source_filename: channable-eligibility.yml
source_heading: Eligibility
source_page: https://www.channable.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Channable\naid: channable\nurl: https://www.channable.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you subscribe to the Service on behalf of a business, you represent to Channable that you have the authority\n    to bind that business\n- type: individual\n  text: Minors under the age of 13 are not permitted to use the Service.\nrestricted_uses:\n- summary: Unlawful or harmful use\n  text: You may not use the Service to disseminate any unlawful or other objectionable material, or to harm others\n    or the\
  \ Service itself.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Minors under the age of 13 are not permitted to use the Service. If the laws of your country of residence\n    so permit, minor children may utilize the Service, provided that their parent or legal guardian establishes\n    the account\n"
source_yaml_url: https://artifacts.apis.io/channable/eligibility/channable-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Channable's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Applicative Saas
- Feed Management
- Marketplace
- E-Commerce
- Product Data
- Order Management
- Advertising
- PPC
- Retail
---
