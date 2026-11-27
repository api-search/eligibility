---
api_specs:
- filename: google-cloud-natural-language-documents-api-openapi.yml
  format: yaml
  label: Google Cloud Natural Language Cloud Natural Language Documents API
  slug: google-cloud-natural-language-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-natural-language/openapi/google-cloud-natural-language-documents-api-openapi.yml
claim_count: 3
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
  - summary: High risk activities
    text: (d) access or use the Services or any AI Agent (i) for High Risk Activities
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
name: Google Cloud Natural Language
provenance_date: '2026-11-09'
provider_name: Google Cloud Natural Language
provider_slug: google-cloud-natural-language
slug: google-cloud-natural-language-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-natural-language-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Natural Language\naid: google-cloud-natural-language\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the entity or person agreeing to these terms\nrestricted_uses:\n- summary: High risk activities\n  text: (d) access or use the Services or any AI Agent (i) for High Risk Activities\n- summary: HIPAA health information\n  text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except\n    as permitted by an executed HIPAA BAA.\n\
  verification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-natural-language/eligibility/google-cloud-natural-language-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Google Cloud Natural Language's own page on 2026-11-09.
synthetic: false
tags:
- Entity Recognition
- Google Cloud
- Machine Learning
- Natural Language Processing
- Sentiment Analysis
- Text Analysis
---
