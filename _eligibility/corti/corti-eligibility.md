---
api_specs:
- filename: corti-transcribe-asyncapi.json
  format: json
  label: Corti Speech to Text API
  slug: corti-speech-to-text-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/corti/asyncapi/corti-transcribe-asyncapi.json
- filename: corti-stream-asyncapi.json
  format: json
  label: Corti Ambient Documentation API
  slug: corti-ambient-documentation-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/corti/asyncapi/corti-stream-asyncapi.json
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you accept or agree to the Agreement on behalf of a company or other legal entity, you represent and warrant that you have the authority to bind that company or other legal entity to the Agreement
    type: business
  minimum_age:
    text: null
    value: null
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
name: Corti
provenance_date: '2026-11-09'
provider_name: Corti
provider_slug: corti
slug: corti-eligibility
source_date: '2026-11-09'
source_filename: corti-eligibility.yml
source_heading: Eligibility
source_page: https://corti.ai/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Corti\naid: corti\nurl: https://corti.ai/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you accept or agree to the Agreement on behalf of a company or other legal entity, you represent and\n    warrant that you have the authority to bind that company or other legal entity to the Agreement\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/corti/eligibility/corti-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Corti's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Artificial Intelligence
- Speech-to-Text
- Medical Coding
- Clinical Documentation
- Agents
- Machine Learning
- Real-Time
---
