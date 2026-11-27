---
api_specs:
- filename: google-cloud-app-engine-apps-api-openapi.yml
  format: yaml
  label: Google Cloud App Engine Apps API
  slug: google-cloud-app-engine-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-app-engine/openapi/google-cloud-app-engine-apps-api-openapi.yml
- filename: google-cloud-app-engine-projects-api-openapi.yml
  format: yaml
  label: Google Cloud App Engine Projects API
  slug: google-cloud-app-engine-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-app-engine/openapi/google-cloud-app-engine-projects-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or person agreeing to these terms ("Customer")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Activities
    text: access or use the Services or any AI Agent (i) for High Risk Activities
  - summary: Health information under HIPAA
    text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA
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
name: Google Cloud App Engine
provenance_date: '2026-11-09'
provider_name: Google Cloud App Engine
provider_slug: google-cloud-app-engine
slug: google-cloud-app-engine-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-app-engine-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud App Engine\naid: google-cloud-app-engine\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity or person agreeing to these terms (\"Customer\")\nrestricted_uses:\n- summary: High Risk Activities\n  text: access or use the Services or any AI Agent (i) for High Risk Activities\n- summary: Health information under HIPAA\n  text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except\n    as permitted by an executed\
  \ HIPAA BAA\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-app-engine/eligibility/google-cloud-app-engine-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Google Cloud App Engine's own page on 2026-11-09.
synthetic: false
tags:
- App Engine
- Compute
- Google Cloud
- Platform-as-a-Service
- Serverless
- Web Applications
---
