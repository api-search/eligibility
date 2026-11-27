---
api_specs:
- filename: google-cloud-data-fusion-projects-api-openapi.yml
  format: yaml
  label: Google Cloud Data Fusion Cloud Data Fusion Projects API
  slug: google-cloud-data-fusion-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-data-fusion/openapi/google-cloud-data-fusion-projects-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: entered into by Google and the entity or person agreeing to these terms ("Customer")
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Activities
    text: access or use the Services or any AI Agent (i) for High Risk Activities;
  - summary: Export-controlled or ITAR materials
    text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR) maintained by the United States Department of State;
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
name: Google Cloud Data Fusion
provenance_date: '2026-11-09'
provider_name: Google Cloud Data Fusion
provider_slug: google-cloud-data-fusion
slug: google-cloud-data-fusion-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-data-fusion-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Data Fusion\naid: google-cloud-data-fusion\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: entered into by Google and the entity or person agreeing to these terms (\"Customer\")\nrestricted_uses:\n- summary: High Risk Activities\n  text: access or use the Services or any AI Agent (i) for High Risk Activities;\n- summary: Export-controlled or ITAR materials\n  text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)\n\
  \    maintained by the United States Department of State;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-data-fusion/eligibility/google-cloud-data-fusion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Google Cloud Data Fusion's own page on 2026-11-09.
synthetic: false
tags:
- Data Integration
- Data Pipeline
- ETL
- Google Cloud
- ELT
- CDAP
---
