---
api_specs:
- filename: actionpower-nlp-api-openapi.yml
  format: yaml
  label: Actionpower NLP API
  slug: actionpower-nlp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionpower/openapi/actionpower-nlp-api-openapi.yml
- filename: actionpower-stt-api-openapi.yml
  format: yaml
  label: Actionpower STT API
  slug: actionpower-stt-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionpower/openapi/actionpower-stt-api-openapi.yml
- filename: actionpower-tts-api-openapi.yml
  format: yaml
  label: Actionpower TTS API
  slug: actionpower-tts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/actionpower/openapi/actionpower-tts-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual or corporation that has registered as a member
    type: individual
  - text: an individual or corporation that has registered as a member
    type: business
  minimum_age:
    text: Where a child under the age of 14 has not obtained the consent of a legal representative (such as a parent)
    value: '14'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: the Company may request real-name verification and identity authentication through a specialized institution depending on the type of member. The Company shall, in principle, accept the Applicant's application to use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Actionpower
provenance_date: '2026-11-09'
provider_name: Actionpower
provider_slug: actionpower
slug: actionpower-eligibility
source_date: '2026-11-09'
source_filename: actionpower-eligibility.yml
source_heading: Eligibility
source_page: https://daglo.ai/d/en/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Actionpower\naid: actionpower\nurl: https://daglo.ai/d/en/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual or corporation that has registered as a member\n- type: business\n  text: an individual or corporation that has registered as a member\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: the Company may request real-name verification and identity authentication through a specialized institution\n    depending on the type of member. The Company shall, in principle,\
  \ accept the Applicant's application to use\n    the Service.\nminimum_age:\n  value: '14'\n  text: Where a child under the age of 14 has not obtained the consent of a legal representative (such as a parent)\n"
source_yaml_url: https://artifacts.apis.io/actionpower/eligibility/actionpower-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Actionpower's own page on 2026-11-09.
synthetic: false
tags:
- Speech Recognition
- Speech-to-Text
- Text-to-Speech
- Natural Language Processing
- Artificial Intelligence
- Transcription
- Voice
- Meeting Intelligence
- gRPC
- South Korea
---
