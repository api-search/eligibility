---
api_specs:
- filename: krisp-sdk-distribution-api-openapi.yml
  format: yaml
  label: Krisp SDK Distribution API
  slug: krisp-sdk-distribution-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/krisp/openapi/krisp-sdk-distribution-api-openapi.yml
- filename: krisp-voice-translation-api-openapi.yml
  format: yaml
  label: Krisp Voice Translation API
  slug: krisp-voice-translation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/krisp/openapi/krisp-voice-translation-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: individual Customers or Authorized Users
    type: individual
  - text: If the individual accepting these Terms is accepting on behalf of a company or other legal entity, such individual represents that they have the authority to bind such entity
    type: business
  minimum_age:
    text: you are of legal age and capacity to enter into a binding agreement
    value: legal age
  restricted_uses:
  - summary: Hazardous or safety-critical uses
    text: use Krisp in, or in association with, the design, construction, maintenance, or operation of any hazardous environments or systems, including any power generation systems
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
name: Krisp
provenance_date: '2026-11-09'
provider_name: Krisp
provider_slug: krisp
slug: krisp-eligibility
source_date: '2026-11-09'
source_filename: krisp-eligibility.yml
source_heading: Eligibility
source_page: https://krisp.ai/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Krisp\naid: krisp\nurl: https://krisp.ai/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: individual Customers or Authorized Users\n- type: business\n  text: If the individual accepting these Terms is accepting on behalf of a company or other legal entity, such\n    individual represents that they have the authority to bind such entity\nrestricted_uses:\n- summary: Hazardous or safety-critical uses\n  text: use Krisp in, or in association with, the design, construction, maintenance, or operation of any\
  \ hazardous\n    environments or systems, including any power generation systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: you are of legal age and capacity to enter into a binding agreement\n"
source_yaml_url: https://artifacts.apis.io/krisp/eligibility/krisp-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Krisp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voice AI
- Speech
- Audio
- Noise Cancellation
- Speech Translation
- Real-Time Communication
- WebRTC
- Conversational AI
- SDK
- Machine Learning
- Real-Time
---
