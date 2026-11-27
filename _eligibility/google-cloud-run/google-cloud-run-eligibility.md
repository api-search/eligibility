---
api_specs:
- filename: google-cloud-run-projects-api-openapi.yml
  format: yaml
  label: Google Cloud Run Projects API
  slug: google-cloud-run-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-run/openapi/google-cloud-run-projects-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or person agreeing to these terms ("Customer")
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: ITAR-controlled materials
    text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR) maintained by the United States Department of State
  - summary: HIPAA health information
    text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA.
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
name: Google Cloud Run
provenance_date: '2026-11-09'
provider_name: Google Cloud Run
provider_slug: google-cloud-run
slug: google-cloud-run-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-run-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Run\naid: google-cloud-run\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the entity or person agreeing to these terms (\"Customer\")\nrestricted_uses:\n- summary: ITAR-controlled materials\n  text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)\n    maintained by the United States Department of State\n- summary: HIPAA health information\n  text: (ix) to transmit, store, or process health information subject\
  \ to United States HIPAA regulations except\n    as permitted by an executed HIPAA BAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-run/eligibility/google-cloud-run-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Google Cloud Run's own page on 2026-11-09.
synthetic: false
tags:
- Cloud Run
- Containers
- Google Cloud
- Serverless
- Platform-as-a-Service
---
