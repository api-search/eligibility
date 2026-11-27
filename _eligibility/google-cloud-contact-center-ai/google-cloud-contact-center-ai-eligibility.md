---
api_specs:
- filename: google-cloud-contact-center-ai-projects-api-openapi.yml
  format: yaml
  label: Google Cloud Contact Center AI Projects API
  slug: google-cloud-contact-center-ai-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/google-cloud-contact-center-ai/openapi/google-cloud-contact-center-ai-projects-api-openapi.yml
claim_count: 4
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
    text: (d) access or use the Services or any AI Agent (i) for High Risk Activities;
  - summary: ITAR-controlled materials
    text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR) maintained by the United States Department of State;
  - summary: Health information without BAA
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
name: Google Cloud Contact Center AI
provenance_date: '2026-11-09'
provider_name: Google Cloud Contact Center AI
provider_slug: google-cloud-contact-center-ai
slug: google-cloud-contact-center-ai-eligibility
source_date: '2026-11-09'
source_filename: google-cloud-contact-center-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cloud.google.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Google Cloud Contact Center AI\naid: google-cloud-contact-center-ai\nurl: https://cloud.google.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity or person agreeing to these terms (\"Customer\")\nrestricted_uses:\n- summary: High Risk Activities\n  text: (d) access or use the Services or any AI Agent (i) for High Risk Activities;\n- summary: ITAR-controlled materials\n  text: (vii) for materials or activities that are subject to the International Traffic in Arms Regulations (ITAR)\n    maintained\
  \ by the United States Department of State;\n- summary: Health information without BAA\n  text: (ix) to transmit, store, or process health information subject to United States HIPAA regulations except\n    as permitted by an executed HIPAA BAA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/google-cloud-contact-center-ai/eligibility/google-cloud-contact-center-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Google Cloud Contact Center AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Contact Center
- Conversations
- Customer Service
- Google Cloud
- Virtual Agents
---
