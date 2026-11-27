---
api_specs:
- filename: profit-rhino-auth-api-openapi.yml
  format: yaml
  label: Profit Rhino Auth API
  slug: profit-rhino-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-auth-api-openapi.yml
- filename: profit-rhino-businessinformation-api-openapi.yml
  format: yaml
  label: Profit Rhino Business Information API
  slug: profit-rhino-businessinformation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-businessinformation-api-openapi.yml
- filename: profit-rhino-manufacturer-api-openapi.yml
  format: yaml
  label: Profit Rhino Manufacturer API
  slug: profit-rhino-manufacturer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-manufacturer-api-openapi.yml
- filename: profit-rhino-optionboard-api-openapi.yml
  format: yaml
  label: Profit Rhino Option Board API
  slug: profit-rhino-optionboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-optionboard-api-openapi.yml
- filename: profit-rhino-partcategory-api-openapi.yml
  format: yaml
  label: Profit Rhino Part Category API
  slug: profit-rhino-partcategory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-partcategory-api-openapi.yml
- filename: profit-rhino-parts-api-openapi.yml
  format: yaml
  label: Profit Rhino Parts API
  slug: profit-rhino-parts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-parts-api-openapi.yml
- filename: profit-rhino-partsmarkup-api-openapi.yml
  format: yaml
  label: Profit Rhino Parts Markup API
  slug: profit-rhino-partsmarkup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-partsmarkup-api-openapi.yml
- filename: profit-rhino-taskcategory-api-openapi.yml
  format: yaml
  label: Profit Rhino Task Category API
  slug: profit-rhino-taskcategory-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-taskcategory-api-openapi.yml
- filename: profit-rhino-tasks-api-openapi.yml
  format: yaml
  label: Profit Rhino Tasks API
  slug: profit-rhino-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-tasks-api-openapi.yml
- filename: profit-rhino-vendors-api-openapi.yml
  format: yaml
  label: Profit Rhino Vendors API
  slug: profit-rhino-vendors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/profit-rhino/openapi/profit-rhino-vendors-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: including any entity completing a sales order (“Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: HIPAA or PCI regulated data
    text: (e) store data on the Services that is regulated by the HIPAA Privacy Rules or the PCI Data Standards
  - summary: Export controls and sanctions
    text: Customer must comply with United States, foreign and international laws and regulations, including without limitation, the United States Export Administration Regulations and the United States Office of Foreign Asset Control regulations
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
name: Profit Rhino
provenance_date: '2026-11-10'
provider_name: Profit Rhino
provider_slug: profit-rhino
slug: profit-rhino-eligibility
source_date: '2026-11-10'
source_filename: profit-rhino-eligibility.yml
source_heading: Eligibility
source_page: https://profitrhino.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Profit Rhino\naid: profit-rhino\nurl: https://profitrhino.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: including any entity completing a sales order (“Customer”)\nrestricted_uses:\n- summary: HIPAA or PCI regulated data\n  text: (e) store data on the Services that is regulated by the HIPAA Privacy Rules or the PCI Data Standards\n- summary: Export controls and sanctions\n  text: Customer must comply with United States, foreign and international laws and regulations, including without\n    limitation, the United\
  \ States Export Administration Regulations and the United States Office of Foreign Asset\n    Control regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/profit-rhino/eligibility/profit-rhino-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Profit Rhino's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Flat-rate
- Contractor
- HVAC
- Software
- sales-tool
---
