---
api_specs:
- filename: google-cloud-functions-projects-api-openapi.yml
  format: yaml
  label: Google Cloud Functions Cloud Functions Projects API
  slug: google-cloud-functions-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-functions/openapi/google-cloud-functions-projects-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or person agreeing to these terms ("Customer")
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Activities
    text: access or use the Services or any AI Agent (i) for High Risk Activities
  - summary: ITAR-controlled materials
    text: for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must have an Account to use the Services
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Cloud Functions
provenance_date: '2026-11-09'
provider_name: Google Cloud Functions
provider_slug: google-cloud-functions
slug: google-cloud-functions-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-functions-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Functions\naid: google-cloud-functions\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the entity or person agreeing to these terms (\"Customer\")\nrestricted_uses:\n- summary: High Risk Activities\n  text: access or use the Services or any AI Agent (i) for High Risk Activities\n- summary: ITAR-controlled materials\n  text: for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: Customer must have an Account to use the Services\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-functions/eligibility/google-cloud-functions-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Google Cloud Functions's own page on 2026-11-09.
synthetic: false
tags:
- Event-Driven
- Functions
- Google Cloud
- Serverless
---
