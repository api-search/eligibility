---
api_specs:
- filename: salsify-digital-assets-api-openapi.yml
  format: yaml
  label: Salsify Digital Assets API
  slug: salsify-digital-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-digital-assets-api-openapi.yml
- filename: salsify-export-runs-api-openapi.yml
  format: yaml
  label: Salsify Export Runs API
  slug: salsify-export-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-export-runs-api-openapi.yml
- filename: salsify-imports-api-openapi.yml
  format: yaml
  label: Salsify Imports API
  slug: salsify-imports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-imports-api-openapi.yml
- filename: salsify-lists-api-openapi.yml
  format: yaml
  label: Salsify Lists API
  slug: salsify-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-lists-api-openapi.yml
- filename: salsify-org-id-api-openapi.yml
  format: yaml
  label: Salsify <org ID> API
  slug: salsify-org-id-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-org-id-api-openapi.yml
- filename: salsify-products-api-openapi.yml
  format: yaml
  label: Salsify Products API
  slug: salsify-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-products-api-openapi.yml
- filename: salsify-properties-api-openapi.yml
  format: yaml
  label: Salsify Properties API
  slug: salsify-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-properties-api-openapi.yml
- filename: salsify-record-types-api-openapi.yml
  format: yaml
  label: Salsify Record Types API
  slug: salsify-record-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-record-types-api-openapi.yml
- filename: salsify-records-api-openapi.yml
  format: yaml
  label: Salsify Records API
  slug: salsify-records-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salsify/openapi/salsify-records-api-openapi.yml
claim_count: 1
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
  - summary: Export controls and sanctions
    text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications
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
name: Salsify
provenance_date: '2026-11-10'
provider_name: Salsify
provider_slug: salsify
slug: salsify-eligibility
source_date: '2026-11-10'
source_filename: salsify-eligibility.yml
source_heading: Eligibility
source_page: https://www.salsify.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Salsify\naid: salsify\nurl: https://www.salsify.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export controls and sanctions\n  text: used for any purposes prohibited by the Export Laws, including, but not limited to, nuclear, chemical, or\n    biological weapons proliferation, missile systems or technology, or restricted unmanned aerial vehicle applications\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/salsify/eligibility/salsify-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Salsify's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Product Experience Management
- Product Information Management
- Digital Asset Management
- Commerce
- Retail
- Syndication
- Data Management
- Software-as-a-Service
---
