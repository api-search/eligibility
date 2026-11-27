---
api_specs:
- filename: kugelaudio-dictionaries-api-openapi.yml
  format: yaml
  label: KugelAudio Dictionaries API
  slug: kugelaudio-dictionaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-dictionaries-api-openapi.yml
- filename: kugelaudio-models-api-openapi.yml
  format: yaml
  label: KugelAudio Models API
  slug: kugelaudio-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-models-api-openapi.yml
- filename: kugelaudio-voices-api-openapi.yml
  format: yaml
  label: KugelAudio Voices API
  slug: kugelaudio-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-voices-api-openapi.yml
- filename: kugelaudio-elevenlabs-compatible-api-openapi.yml
  format: yaml
  label: KugelAudio ElevenLabs compatible API
  slug: kugelaudio-elevenlabs-compatible-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-elevenlabs-compatible-api-openapi.yml
- filename: kugelaudio-projects-api-openapi.yml
  format: yaml
  label: KugelAudio Projects API
  slug: kugelaudio-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-projects-api-openapi.yml
- filename: kugelaudio-text-to-speech-api-openapi.yml
  format: yaml
  label: KugelAudio Text to Speech API
  slug: kugelaudio-text-to-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kugelaudio/openapi/kugelaudio-text-to-speech-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: any natural person who concludes the contract for purposes that are predominantly outside their trade, business or profession
    type: individual
  - text: a user within the meaning of Section 14 BGB
    type: business
  minimum_age:
    text: The Service is intended for persons aged 18 or over.
    value: '18'
  restricted_uses:
  - summary: Consent for other people's voices
    text: For another person's voice, express, documented consent must at least cover creation and use of the customer-specific voice model
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Before activation or continued use, KugelAudio may require evidence of rights and consent, identity or voice verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: KugelAudio
provenance_date: '2026-11-09'
provider_name: KugelAudio
provider_slug: kugelaudio
slug: kugelaudio-eligibility
source_date: '2026-11-09'
source_filename: kugelaudio-eligibility.yml
source_heading: Eligibility
source_page: https://www.kugelaudio.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: KugelAudio\naid: kugelaudio\nurl: https://www.kugelaudio.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: any natural person who concludes the contract for purposes that are predominantly outside their trade, business\n    or profession\n- type: business\n  text: a user within the meaning of Section 14 BGB\nrestricted_uses:\n- summary: Consent for other people's voices\n  text: For another person's voice, express, documented consent must at least cover creation and use of the customer-specific\n    voice model\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: Before activation or continued use, KugelAudio may require evidence of rights and consent, identity or voice\n    verification.\nminimum_age:\n  value: '18'\n  text: The Service is intended for persons aged 18 or over.\n"
source_yaml_url: https://artifacts.apis.io/kugelaudio/eligibility/kugelaudio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from KugelAudio's own page on 2026-11-09.
synthetic: false
tags:
- Voice
- Text-to-Speech
- Speech Synthesis
- Voice AI
- Voice Cloning
- Audio
- Artificial Intelligence
- Machine Learning
- Streaming
- Real-Time
- Conversational AI
- Europe
- Data Sovereignty
- GDPR
- Company
---
