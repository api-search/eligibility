---
api_specs:
- filename: lalal-ai-batch-stem-separation-api-openapi.yml
  format: yaml
  label: LALAL.AI Batch Stem Separation API
  slug: lalal-ai-batch-stem-separation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lalal-ai/openapi/lalal-ai-batch-stem-separation-api-openapi.yml
- filename: lalal-ai-common-api-openapi.yml
  format: yaml
  label: LALAL.AI Common API
  slug: lalal-ai-common-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lalal-ai/openapi/lalal-ai-common-api-openapi.yml
- filename: lalal-ai-stem-separation-api-openapi.yml
  format: yaml
  label: LALAL.AI Stem Separation API
  slug: lalal-ai-stem-separation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lalal-ai/openapi/lalal-ai-stem-separation-api-openapi.yml
- filename: lalal-ai-voice-change-api-openapi.yml
  format: yaml
  label: LALAL.AI Voice Change API
  slug: lalal-ai-voice-change-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lalal-ai/openapi/lalal-ai-voice-change-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you represent and warrant that (i) you are of legal age to form a binding contract
    type: individual
  minimum_age:
    text: you are of legal age to form a binding contract
    value: null
  restricted_uses:
  - summary: No impersonation
    text: You are strictly prohibited from using Services to impersonate individuals without legal authorization or to falsely represent synthetic audio as authentic human speech.
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
name: LALAL.AI
provenance_date: '2026-11-09'
provider_name: LALAL.AI
provider_slug: lalal-ai
slug: lalal-ai-eligibility
source_date: '2026-11-09'
source_filename: lalal-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.lalal.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LALAL.AI\naid: lalal-ai\nurl: https://www.lalal.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you represent and warrant that (i) you are of legal age to form a binding contract\nrestricted_uses:\n- summary: No impersonation\n  text: You are strictly prohibited from using Services to impersonate individuals without legal authorization or\n    to falsely represent synthetic audio as authentic human speech.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: you are of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/lalal-ai/eligibility/lalal-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from LALAL.AI's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Audio
- Audio Processing
- Stem Separation
- Vocal Removal
- Voice Cleaning
- Voice Cloning
- Voice Changer
- Music
- Machine Learning
- Digital Signal Processing
---
