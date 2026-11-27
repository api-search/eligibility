---
api_specs:
- filename: rhumbix-batch-export-api-openapi.yml
  format: yaml
  label: Rhumbix Batch Export API
  slug: rhumbix-batch-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhumbix/openapi/rhumbix-batch-export-api-openapi.yml
- filename: rhumbix-batch-import-api-openapi.yml
  format: yaml
  label: Rhumbix Batch Import API
  slug: rhumbix-batch-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhumbix/openapi/rhumbix-batch-import-api-openapi.yml
- filename: rhumbix-cors-api-openapi.yml
  format: yaml
  label: Rhumbix CORS API
  slug: rhumbix-cors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rhumbix/openapi/rhumbix-cors-api-openapi.yml
claim_count: 2
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
  - summary: Timekeeping office worker licence scope
    text: Timekeeping Office Worker Licenses are restricted solely to the entering and viewing of their own time entered into Rhumbix.
  - summary: Sandbox data not migratable
    text: Cannot be migrated to any other Rhumbix environment.
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
name: Rhumbix
provenance_date: '2026-11-10'
provider_name: Rhumbix
provider_slug: rhumbix
slug: rhumbix-eligibility
source_date: '2026-11-10'
source_filename: rhumbix-eligibility.yml
source_heading: Eligibility
source_page: https://www.rhumbix.com/service_terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rhumbix\naid: rhumbix\nurl: https://www.rhumbix.com/service_terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Timekeeping office worker licence scope\n  text: Timekeeping Office Worker Licenses are restricted solely to the entering and viewing of their own time entered\n    into Rhumbix.\n- summary: Sandbox data not migratable\n  text: Cannot be migrated to any other Rhumbix environment.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rhumbix/eligibility/rhumbix-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Rhumbix's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Application
- Construction
- Construction Technology
- Workforce Management
- Timekeeping
- Payroll
- Field Data Collection
- Project Management
- Job Costing
- Integration
- REST API
---
