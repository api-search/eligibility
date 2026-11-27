---
api_specs:
- filename: kotoba-transcriptionapi-api-openapi.yml
  format: yaml
  label: Kotoba Transcription API
  slug: kotoba-transcriptionapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kotoba/openapi/kotoba-transcriptionapi-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We make no representation that the Services are appropriate or available for use in any particular jurisdiction. You represent that you are not located in any country subject to comprehensive sanctions.
  entity_types:
  - text: If you accept or agree to the Agreement on behalf of a company or other legal entity, including as an enterprise customer, you represent and warrant that you have the authority to bind that company
    type: business
  minimum_age:
    text: The Services are not intended for use by individuals under the age of 13, and you must be at least 13 years of age to create an account or use the Services.
    value: '13'
  restricted_uses:
  - summary: Regulated data not permitted
    text: The Services are not designed or intended to process data subject to specific regulatory frameworks, including protected health information subject to the Health Insurance Portability and Accountability Act ("HIPAA")
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
name: Kotoba
provenance_date: '2026-11-09'
provider_name: Kotoba
provider_slug: kotoba
slug: kotoba-eligibility
source_date: '2026-11-09'
source_filename: kotoba-eligibility.yml
source_heading: Eligibility
source_page: https://dashboard.kotobatech.ai/terms_en.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kotoba\naid: kotoba\nurl: https://dashboard.kotobatech.ai/terms_en.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We make no representation that the Services are appropriate or available for use in any particular jurisdiction.\n    You represent that you are not located in any country subject to comprehensive sanctions.\nentity_types:\n- type: business\n  text: If you accept or agree to the Agreement on behalf of a company or other legal entity, including as an enterprise\n    customer, you represent and warrant that you have the authority to bind that company\nrestricted_uses:\n\
  - summary: Regulated data not permitted\n  text: The Services are not designed or intended to process data subject to specific regulatory frameworks, including\n    protected health information subject to the Health Insurance Portability and Accountability Act (\"HIPAA\")\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are not intended for use by individuals under the age of 13, and you must be at least 13 years\n    of age to create an account or use the Services.\n"
source_yaml_url: https://artifacts.apis.io/kotoba/eligibility/kotoba-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kotoba's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Voice
- Speech Recognition
- Speech-to-Text
- Text-to-Speech
- Translation
- Real-Time
- WebSocket
- Audio
- Transcription
---
