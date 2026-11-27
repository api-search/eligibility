---
api_specs:
- filename: best-practice-fhir-api-openapi.yml
  format: yaml
  label: Best Practice Software FHIR API
  slug: best-practice-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-fhir-api-openapi.yml
- filename: best-practice-registered-queries-api-openapi.yml
  format: yaml
  label: Best Practice Software Registered Queries API
  slug: best-practice-registered-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-registered-queries-api-openapi.yml
- filename: best-practice-sites-api-openapi.yml
  format: yaml
  label: Best Practice Software Sites API
  slug: best-practice-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-sites-api-openapi.yml
- filename: best-practice-sql-passthrough-api-openapi.yml
  format: yaml
  label: Best Practice Software SQL Passthrough API
  slug: best-practice-sql-passthrough-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-sql-passthrough-api-openapi.yml
- filename: best-practice-tokens-api-openapi.yml
  format: yaml
  label: Best Practice Software Tokens API
  slug: best-practice-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/best-practice/openapi/best-practice-tokens-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    - NZ
    text: content is intended only for residents of Australia and New Zealand.
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
name: Best Practice Software
provenance_date: '2026-11-09'
provider_name: Best Practice Software
provider_slug: best-practice
slug: best-practice-eligibility
source_date: '2026-11-09'
source_filename: best-practice-eligibility.yml
source_heading: Eligibility
source_page: https://bestpracticesoftware.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Best Practice Software\naid: best-practice\nurl: https://bestpracticesoftware.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  - NZ\n  excluded: []\n  text: content is intended only for residents of Australia and New Zealand.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/best-practice/eligibility/best-practice-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Best Practice Software's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Australia
- Electronic Health Records
- FHIR
- HL7
- Interoperability
- AU Base
- Practice Management
- General Practice
- Appointments
- Scheduling
---
