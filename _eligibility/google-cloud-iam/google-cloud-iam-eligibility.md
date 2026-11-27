---
api_specs:
- filename: google-cloud-iam-folders-api-openapi.yml
  format: yaml
  label: Google Cloud IAM Folders API
  slug: google-cloud-iam-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-iam/openapi/google-cloud-iam-folders-api-openapi.yml
- filename: google-cloud-iam-iam-api-openapi.yml
  format: yaml
  label: Google Cloud IAM Iam API
  slug: google-cloud-iam-iam-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-iam/openapi/google-cloud-iam-iam-api-openapi.yml
- filename: google-cloud-iam-locations-api-openapi.yml
  format: yaml
  label: Google Cloud IAM Locations API
  slug: google-cloud-iam-locations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-iam/openapi/google-cloud-iam-locations-api-openapi.yml
- filename: google-cloud-iam-operations-api-openapi.yml
  format: yaml
  label: Google Cloud IAM Operations API
  slug: google-cloud-iam-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-iam/openapi/google-cloud-iam-operations-api-openapi.yml
- filename: google-cloud-iam-organizations-api-openapi.yml
  format: yaml
  label: Google Cloud IAM Organizations API
  slug: google-cloud-iam-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-iam/openapi/google-cloud-iam-organizations-api-openapi.yml
- filename: google-cloud-iam-policies-api-openapi.yml
  format: yaml
  label: Google Cloud IAM Policies API
  slug: google-cloud-iam-policies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-iam/openapi/google-cloud-iam-policies-api-openapi.yml
- filename: google-cloud-iam-projects-api-openapi.yml
  format: yaml
  label: Google Cloud IAM Projects API
  slug: google-cloud-iam-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-iam/openapi/google-cloud-iam-projects-api-openapi.yml
- filename: google-cloud-iam-token-api-openapi.yml
  format: yaml
  label: Google Cloud IAM Token API
  slug: google-cloud-iam-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-iam/openapi/google-cloud-iam-token-api-openapi.yml
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
  - summary: ITAR-controlled materials
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
name: Google Cloud IAM
provenance_date: '2026-11-09'
provider_name: Google Cloud IAM
provider_slug: google-cloud-iam
slug: google-cloud-iam-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-iam-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud IAM\naid: google-cloud-iam\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the entity or person agreeing to these terms (\"Customer\")\nrestricted_uses:\n- summary: High Risk Activities\n  text: (d) access or use the Services or any AI Agent (i) for High Risk Activities;\n- summary: ITAR-controlled materials\n  text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)\n    maintained by the United States Department\
  \ of State;\n- summary: Health information under HIPAA\n  text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except\n    as permitted by an executed HIPAA BAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must verify a Domain Email Address or a Domain Name to use GWS Services or Cloud Identity Services.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-iam/eligibility/google-cloud-iam-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 5 quoted statements, read from Google Cloud IAM's own page on 2026-11-09.
synthetic: false
tags:
- Identity and Access Management
- Google Cloud
- Identity
- Permissions
- Security
---
