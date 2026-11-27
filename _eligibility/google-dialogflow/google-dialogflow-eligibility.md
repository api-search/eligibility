---
api_specs:
- filename: google-dialogflow-projects-api-openapi.yml
  format: yaml
  label: Google Dialogflow Projects API
  slug: google-dialogflow-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-dialogflow/openapi/google-dialogflow-projects-api-openapi.yml
claim_count: 4
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
  - summary: High Risk Activities
    text: access or use the Services or any AI Agent (i) for High Risk Activities
  - summary: Health information under HIPAA
    text: to transmit, store, or process health information subject to United States HIPAA regulations except as permitted by an executed HIPAA BAA
  - summary: ITAR-controlled materials
    text: for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Customer must have an Account to use the Services and is responsible for the information it provides to create the Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Google Dialogflow
provenance_date: '2026-11-09'
provider_name: Google Dialogflow
provider_slug: google-dialogflow
slug: google-dialogflow-eligibility
source_date: '2026-11-09'
source_filename: google-dialogflow-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Dialogflow\naid: google-dialogflow\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High Risk Activities\n  text: access or use the Services or any AI Agent (i) for High Risk Activities\n- summary: Health information under HIPAA\n  text: to transmit, store, or process health information subject to United States HIPAA regulations except as permitted\n    by an executed HIPAA BAA\n- summary: ITAR-controlled materials\n  text: for materials or activities that are subject\
  \ to the International Traffic in Arms Regulations (ITAR)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Customer must have an Account to use the Services and is responsible for the information it provides to\n    create the Account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-dialogflow/eligibility/google-dialogflow-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Google Dialogflow's own page on 2026-11-09.
synthetic: false
tags:
- Agents
- Artificial Intelligence
- Chatbots
- Conversational AI
- Google Cloud
- Machine Learning
- Natural Language Processing
- Speech Recognition
- Virtual Agents
- Voice Assistant
---
