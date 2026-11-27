---
api_specs:
- filename: google-cloud-endpoints-operations-api-openapi.yml
  format: yaml
  label: Google Cloud Endpoints Operations API
  slug: google-cloud-endpoints-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-endpoints/openapi/google-cloud-endpoints-operations-api-openapi.yml
- filename: google-cloud-endpoints-services-api-openapi.yml
  format: yaml
  label: Google Cloud Endpoints Services API
  slug: google-cloud-endpoints-services-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-endpoints/openapi/google-cloud-endpoints-services-api-openapi.yml
claim_count: 3
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
  - summary: Health information (HIPAA)
    text: to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA
  - summary: Cryptocurrency mining
    text: to engage in cryptocurrency mining without Google's prior written approval
  - summary: ITAR-controlled materials
    text: for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)
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
name: Google Cloud Endpoints
provenance_date: '2026-11-09'
provider_name: Google Cloud Endpoints
provider_slug: google-cloud-endpoints
slug: google-cloud-endpoints-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-endpoints-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Endpoints\naid: google-cloud-endpoints\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Health information (HIPAA)\n  text: to transmit, store, or process health information subject to United States HIPAA regulations except as permitted\n    by an executed HIPAA BAA\n- summary: Cryptocurrency mining\n  text: to engage in cryptocurrency mining without Google's prior written approval\n- summary: ITAR-controlled materials\n  text: for materials or activities that\
  \ are subject to the International Traffic in Arms Regulations (ITAR)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-endpoints/eligibility/google-cloud-endpoints-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 3 quoted statements, read from Google Cloud Endpoints's own page on 2026-11-09.
synthetic: false
tags:
- API Gateway
- API Management
- Authentication
- Google Cloud
- Monitoring
- Rate Limiting
---
