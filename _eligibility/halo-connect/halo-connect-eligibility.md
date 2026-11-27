---
api_specs:
- filename: halo-connect-fhir-api-openapi.yml
  format: yaml
  label: Halo Connect FHIR API
  slug: halo-connect-fhir-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-fhir-api-openapi.yml
- filename: halo-connect-registered-queries-api-openapi.yml
  format: yaml
  label: Halo Connect Registered Queries API
  slug: halo-connect-registered-queries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-registered-queries-api-openapi.yml
- filename: halo-connect-sites-api-openapi.yml
  format: yaml
  label: Halo Connect Sites API
  slug: halo-connect-sites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-sites-api-openapi.yml
- filename: halo-connect-sql-passthrough-api-openapi.yml
  format: yaml
  label: Halo Connect SQL Passthrough API
  slug: halo-connect-sql-passthrough-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-sql-passthrough-api-openapi.yml
- filename: halo-connect-tokens-api-openapi.yml
  format: yaml
  label: Halo Connect Tokens API
  slug: halo-connect-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/halo-connect/openapi/halo-connect-tokens-api-openapi.yml
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
  - summary: Free Services disclaimers
    text: To the maximum extent permitted by law, we disclaim all obligations or liabilities with respect to the Free Services, including any support, warranty and indemnity obligations.
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
name: Halo Connect
provenance_date: '2026-11-09'
provider_name: Halo Connect
provider_slug: halo-connect
slug: halo-connect-eligibility
source_date: '2026-11-09'
source_filename: halo-connect-eligibility.yml
source_heading: Eligibility
source_page: https://haloconnect.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Halo Connect\naid: halo-connect\nurl: https://haloconnect.io/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Free Services disclaimers\n  text: To the maximum extent permitted by law, we disclaim all obligations or liabilities with respect to the Free\n    Services, including any support, warranty and indemnity obligations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/halo-connect/eligibility/halo-connect-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Halo Connect's own page on 2026-11-09.
synthetic: false
tags:
- Healthcare
- Australia
- FHIR
- HL7
- Interoperability
- Electronic Health Records
- Practice Management
- Primary Care
- AU Base
- Health Data
---
