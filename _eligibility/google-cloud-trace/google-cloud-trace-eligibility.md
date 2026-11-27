---
api_specs:
- filename: google-cloud-trace-projects-api-openapi.yml
  format: yaml
  label: Google Cloud Trace Projects API
  slug: google-cloud-trace-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-trace/openapi/google-cloud-trace-projects-api-openapi.yml
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or person agreeing to these terms
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Activities
    text: (d) access or use the Services or any AI Agent (i) for High Risk Activities;
  - summary: Cryptocurrency mining
    text: (iv) to engage in cryptocurrency mining without Google's prior written approval
  - summary: Export-controlled and ITAR materials
    text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)
  - summary: HIPAA health information without BAA
    text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA.
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
name: Google Cloud Trace
provenance_date: '2026-11-09'
provider_name: Google Cloud Trace
provider_slug: google-cloud-trace
slug: google-cloud-trace-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-trace-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Trace\naid: google-cloud-trace\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the entity or person agreeing to these terms\nrestricted_uses:\n- summary: High Risk Activities\n  text: (d) access or use the Services or any AI Agent (i) for High Risk Activities;\n- summary: Cryptocurrency mining\n  text: (iv) to engage in cryptocurrency mining without Google's prior written approval\n- summary: Export-controlled and ITAR materials\n  text: (vii) for materials or activities\
  \ that are subject to the International Traffic in Arms Regulations (ITAR)\n- summary: HIPAA health information without BAA\n  text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except\n    as permitted by an executed HIPAA BAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must have an Account to use the Services\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-trace/eligibility/google-cloud-trace-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 6 quoted statements, read from Google Cloud Trace's own page on 2026-11-09.
synthetic: false
tags:
- Distributed Tracing
- Google Cloud
- Latency
- Observability
- Performance
- Spans
- Tracing
---
