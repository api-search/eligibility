---
api_specs:
- filename: google-cloud-chronicle-alerts-api-openapi.yml
  format: yaml
  label: Google Cloud Chronicle Alerts API
  slug: google-cloud-chronicle-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-chronicle/openapi/google-cloud-chronicle-alerts-api-openapi.yml
- filename: google-cloud-chronicle-feeds-api-openapi.yml
  format: yaml
  label: Google Cloud Chronicle Feeds API
  slug: google-cloud-chronicle-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-chronicle/openapi/google-cloud-chronicle-feeds-api-openapi.yml
- filename: google-cloud-chronicle-referencelists-api-openapi.yml
  format: yaml
  label: Google Cloud Chronicle ReferenceLists API
  slug: google-cloud-chronicle-referencelists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-chronicle/openapi/google-cloud-chronicle-referencelists-api-openapi.yml
- filename: google-cloud-chronicle-rules-api-openapi.yml
  format: yaml
  label: Google Cloud Chronicle Rules API
  slug: google-cloud-chronicle-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-chronicle/openapi/google-cloud-chronicle-rules-api-openapi.yml
claim_count: 5
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
    text: (d) access or use the Services or any AI Agent (i) for High Risk Activities;
  - summary: Export-controlled and ITAR materials
    text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR) maintained by the United States Department of State;
  - summary: Health information under HIPAA
    text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must verify a Domain Email Address or a Domain Name to use GWS Services or Cloud Identity Services.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Cloud Chronicle
provenance_date: '2026-11-09'
provider_name: Google Cloud Chronicle
provider_slug: google-cloud-chronicle
slug: google-cloud-chronicle-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-chronicle-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Chronicle\naid: google-cloud-chronicle\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the entity or person agreeing to these terms (\"Customer\")\nrestricted_uses:\n- summary: High Risk Activities\n  text: (d) access or use the Services or any AI Agent (i) for High Risk Activities;\n- summary: Export-controlled and ITAR materials\n  text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)\n    maintained by the United\
  \ States Department of State;\n- summary: Health information under HIPAA\n  text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except\n    as permitted by an executed HIPAA BAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must verify a Domain Email Address or a Domain Name to use GWS Services or Cloud Identity Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-chronicle/eligibility/google-cloud-chronicle-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Google Cloud Chronicle's own page on 2026-11-09.
synthetic: false
tags:
- Incident Response
- Log Management
- Security Analytics
- Security Operations
- SIEM
- Threat Detection
---
