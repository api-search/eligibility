---
api_specs:
- filename: google-cloud-binary-authorization-projects-api-openapi.yml
  format: yaml
  label: Google Cloud Binary Authorization Cloud Binary Authorization Projects API
  slug: google-cloud-binary-authorization-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-binary-authorization/openapi/google-cloud-binary-authorization-projects-api-openapi.yml
- filename: google-cloud-binary-authorization-systempolicy-api-openapi.yml
  format: yaml
  label: Google Cloud Binary Authorization Cloud Binary Authorization Systempolicy API
  slug: google-cloud-binary-authorization-systempolicy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-binary-authorization/openapi/google-cloud-binary-authorization-systempolicy-api-openapi.yml
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
    text: (i) for High Risk Activities;
  - summary: Export-controlled or ITAR materials
    text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)
  - summary: HIPAA health information without BAA
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
name: Google Cloud Binary Authorization
provenance_date: '2026-11-09'
provider_name: Google Cloud Binary Authorization
provider_slug: google-cloud-binary-authorization
slug: google-cloud-binary-authorization-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-binary-authorization-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Binary Authorization\naid: google-cloud-binary-authorization\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the entity or person agreeing to these terms (\"Customer\")\nrestricted_uses:\n- summary: High Risk Activities\n  text: (i) for High Risk Activities;\n- summary: Export-controlled or ITAR materials\n  text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)\n- summary: HIPAA health information without BAA\n\
  \  text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except\n    as permitted by an executed HIPAA BAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-binary-authorization/eligibility/google-cloud-binary-authorization-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Google Cloud Binary Authorization's own page on 2026-11-09.
synthetic: false
tags:
- Attestation
- Container Security
- DevSecOps
- Kubernetes
- Policy Enforcement
- Supply Chain Security
---
