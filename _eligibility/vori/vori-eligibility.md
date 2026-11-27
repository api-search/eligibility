---
api_specs:
- filename: vori-store-products-api-openapi.yml
  format: yaml
  label: Vori Store products API
  slug: vori-store-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/vori/openapi/vori-store-products-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: (b) you are located in the United States
  entity_types:
  - text: If you are accessing or using the Vori Services on behalf of your company, you represent that you are authorized to accept this Agreement on behalf of your company
    type: business
  - text: the entity or person accessing or purchasing any of Vori’s products and services
    type: individual
  minimum_age:
    text: (a) you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: No fraudulent use
    text: you will not use the Vori Services, directly or indirectly, for any fraudulent undertaking or in any manner so as to interfere with the operation of the Vori Services
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must register for a Vori account in order to use the Vori Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Vori
provenance_date: '2026-11-10'
provider_name: Vori
provider_slug: vori
slug: vori-eligibility
source_date: '2026-11-10'
source_filename: vori-eligibility.yml
source_heading: Eligibility
source_page: https://www.vori.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Vori\naid: vori\nurl: https://www.vori.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: (b) you are located in the United States\nentity_types:\n- type: business\n  text: If you are accessing or using the Vori Services on behalf of your company, you represent that you are authorized\n    to accept this Agreement on behalf of your company\n- type: individual\n  text: the entity or person accessing or purchasing any of Vori’s products and services\nrestricted_uses:\n- summary: No fraudulent use\n  text: you will not use the Vori Services, directly or indirectly, for any\
  \ fraudulent undertaking or in any manner\n    so as to interfere with the operation of the Vori Services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must register for a Vori account in order to use the Vori Services.\nminimum_age:\n  value: '18'\n  text: (a) you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/vori/eligibility/vori-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Vori's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Application
- Grocery
- Point-of-Sale
- Retail
- Inventory
- Payments
- Commerce
---
