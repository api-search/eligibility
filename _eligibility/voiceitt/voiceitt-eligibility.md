---
api_specs:
- filename: voiceitt-websockets-asyncapi.yml
  format: yaml
  label: Voiceitt WebSockets API
  slug: voiceitt-websockets-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/voiceitt/asyncapi/voiceitt-websockets-asyncapi.yml
- filename: voiceitt-auth-api-openapi.yml
  format: yaml
  label: Voiceitt Auth API
  slug: voiceitt-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voiceitt/openapi/voiceitt-auth-api-openapi.yml
- filename: voiceitt-rec-api-openapi.yml
  format: yaml
  label: Voiceitt Rec API
  slug: voiceitt-rec-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/voiceitt/openapi/voiceitt-rec-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: parent/guardian accepting the Terms on behalf of a minor
    type: other
  minimum_age:
    text: To access and use our Website, Apps, and/or Services, you must be at least 18 years old and have the ability to form a binding contract.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: for personal, non-commercial purposes
  - summary: Lawful use only
    text: You may only use the Website, Apps, and/or Services for lawful purposes and as permitted by these Terms.
  - summary: Not a substitute for medical advice
    text: The use of the Services does not replace any medical treatment or advice to be provided by doctors or other healthcare professionals.
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
name: Voiceitt
provenance_date: '2026-11-10'
provider_name: Voiceitt
provider_slug: voiceitt
slug: voiceitt-eligibility
source_date: '2026-11-10'
source_filename: voiceitt-eligibility.yml
source_heading: Eligibility
source_page: https://www.voiceitt.com/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Voiceitt\naid: voiceitt\nurl: https://www.voiceitt.com/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: parent/guardian accepting the Terms on behalf of a minor\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: for personal, non-commercial purposes\n- summary: Lawful use only\n  text: You may only use the Website, Apps, and/or Services for lawful purposes and as permitted by these Terms.\n- summary: Not a substitute for medical advice\n  text: The use of the Services does not\
  \ replace any medical treatment or advice to be provided by doctors or other\n    healthcare professionals.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: To access and use our Website, Apps, and/or Services, you must be at least 18 years old and have the ability\n    to form a binding contract.\n"
source_yaml_url: https://artifacts.apis.io/voiceitt/eligibility/voiceitt-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Voiceitt's own page on 2026-11-10.
synthetic: false
tags:
- Speech Recognition
- Speech-to-Text
- Voice
- Accessibility
- Assistive Technology
- Artificial Intelligence
- Transcription
- Captioning
- Company
- Real-Time
---
