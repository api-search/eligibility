---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: You warrant that you are (1) not located in Cuba, Iran, North Korea, Sudan, or Syria
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are signing up for the Platform and the Service on behalf of a company (an “Enterprise Customer”), you represent that you are duly authorized to represent such company
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Agora
provenance_date: '2026-11-09'
provider_name: Agora
provider_slug: agora-io
slug: agora-io-eligibility
source_date: '2026-11-09'
source_filename: agora-io-eligibility.yml
source_heading: Eligibility
source_page: https://www.agora.io/en/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agora\naid: agora-io\nurl: https://www.agora.io/en/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: You warrant that you are (1) not located in Cuba, Iran, North Korea, Sudan, or Syria\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are signing up for the Platform and the Service on behalf of a company (an “Enterprise Customer”),\n    you represent that you are duly authorized to represent such company\nrestricted_uses: []\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/agora-io/eligibility/agora-io-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from Agora's own page on 2026-11-09.
synthetic: false
tags:
- Real-Time Engagement
- Voice
- Video
- Signaling
- Conversational AI
- Streaming
- Chat
- Cloud Recording
- WebRTC
- Communications Platform
- Real-Time
---
