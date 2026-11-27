---
api_specs:
- filename: reson8-auth-api-openapi.yml
  format: yaml
  label: Reson8 Auth API
  slug: reson8-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reson8/openapi/reson8-auth-api-openapi.yml
- filename: reson8-custom-models-api-openapi.yml
  format: yaml
  label: Reson8 Custom Models API
  slug: reson8-custom-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reson8/openapi/reson8-custom-models-api-openapi.yml
- filename: reson8-speech-to-text-api-openapi.yml
  format: yaml
  label: Reson8 Speech to Text API
  slug: reson8-speech-to-text-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/reson8/openapi/reson8-speech-to-text-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Customer must (i) be legally able to represent the company or business contracting the Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal or infringing content
    text: Use the Services to process content that is illegal, defamatory, or infringes the rights of any third party;
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
name: Reson8
provenance_date: '2026-11-10'
provider_name: Reson8
provider_slug: reson8
slug: reson8-eligibility
source_date: '2026-11-10'
source_filename: reson8-eligibility.yml
source_heading: Eligibility
source_page: https://www.reson8.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Reson8\naid: reson8\nurl: https://www.reson8.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Customer must (i) be legally able to represent the company or business contracting the Services\nrestricted_uses:\n- summary: Illegal or infringing content\n  text: Use the Services to process content that is illegal, defamatory, or infringes the rights of any third party;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/reson8/eligibility/reson8-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Reson8's own page on 2026-11-10.
synthetic: false
tags:
- Speech Recognition
- Speech-to-Text
- Voice AI
- Transcription
- Diarization
- Machine Learning
- Developers
---
