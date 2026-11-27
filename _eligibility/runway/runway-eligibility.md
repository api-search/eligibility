---
api_specs:
- filename: runway-avatars-api-openapi.yml
  format: yaml
  label: Runway Avatars API
  slug: runway-avatars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-avatars-api-openapi.yml
- filename: runway-character-performance-api-openapi.yml
  format: yaml
  label: Runway Character Performance API
  slug: runway-character-performance-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-character-performance-api-openapi.yml
- filename: runway-documents-api-openapi.yml
  format: yaml
  label: Runway Documents API
  slug: runway-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-documents-api-openapi.yml
- filename: runway-frame-interpolation-api-openapi.yml
  format: yaml
  label: Runway Frame Interpolation API
  slug: runway-frame-interpolation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-frame-interpolation-api-openapi.yml
- filename: runway-image-to-video-api-openapi.yml
  format: yaml
  label: Runway Image to Video API
  slug: runway-image-to-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-image-to-video-api-openapi.yml
- filename: runway-lip-sync-api-openapi.yml
  format: yaml
  label: Runway Lip Sync API
  slug: runway-lip-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-lip-sync-api-openapi.yml
- filename: runway-realtime-sessions-api-openapi.yml
  format: yaml
  label: Runway Realtime Sessions API
  slug: runway-realtime-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-realtime-sessions-api-openapi.yml
- filename: runway-sound-effects-api-openapi.yml
  format: yaml
  label: Runway Sound Effects API
  slug: runway-sound-effects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-sound-effects-api-openapi.yml
- filename: runway-tasks-api-openapi.yml
  format: yaml
  label: Runway Tasks API
  slug: runway-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-tasks-api-openapi.yml
- filename: runway-text-to-image-api-openapi.yml
  format: yaml
  label: Runway Text to Image API
  slug: runway-text-to-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-text-to-image-api-openapi.yml
- filename: runway-text-to-video-api-openapi.yml
  format: yaml
  label: Runway Text to Video API
  slug: runway-text-to-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-text-to-video-api-openapi.yml
- filename: runway-uploads-api-openapi.yml
  format: yaml
  label: Runway Uploads API
  slug: runway-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-uploads-api-openapi.yml
- filename: runway-video-to-video-api-openapi.yml
  format: yaml
  label: Runway Video to Video API
  slug: runway-video-to-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-video-to-video-api-openapi.yml
- filename: runway-video-upscale-api-openapi.yml
  format: yaml
  label: Runway Video Upscale API
  slug: runway-video-upscale-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-video-upscale-api-openapi.yml
- filename: runway-organization-api-openapi.yml
  format: yaml
  label: Runway Organization API
  slug: runway-organization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-organization-api-openapi.yml
- filename: runway-text-to-speech-api-openapi.yml
  format: yaml
  label: Runway Text To Speech API
  slug: runway-text-to-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runway/openapi/runway-text-to-speech-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and offered by Company from its facilities in the United States of America. Company makes no representations that the Services are appropriate or available for use in other locations.
  entity_types:
  - text: YOU HAVE THE AUTHORITY TO ENTER INTO THE TERMS OF USE PERSONALLY OR ON BEHALF OF THE ENTITY YOU HAVE NAMED AS THE USER
    type: business
  minimum_age:
    text: You represent that you are (i) at least thirteen (13) years old, (ii) of legal age to form a binding contract
    value: '13'
  restricted_uses:
  - summary: Prohibited apps
    text: (vii) sell or promote illegal or regulated goods or services such as gambling, controlled substances, weapons, financial, legal, or medical services
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
name: Runway
provenance_date: '2026-11-10'
provider_name: Runway
provider_slug: runway
slug: runway-eligibility
source_date: '2026-11-10'
source_filename: runway-eligibility.yml
source_heading: Eligibility
source_page: https://runway.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Runway\naid: runway\nurl: https://runway.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and offered by Company from its facilities in the United States of America.\n    Company makes no representations that the Services are appropriate or available for use in other locations.\nentity_types:\n- type: business\n  text: YOU HAVE THE AUTHORITY TO ENTER INTO THE TERMS OF USE PERSONALLY OR ON BEHALF OF THE ENTITY YOU HAVE NAMED\n    AS THE USER\nrestricted_uses:\n- summary: Prohibited apps\n  text: (vii) sell or promote illegal\
  \ or regulated goods or services such as gambling, controlled substances, weapons,\n    financial, legal, or medical services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You represent that you are (i) at least thirteen (13) years old, (ii) of legal age to form a binding contract\n"
source_yaml_url: https://artifacts.apis.io/runway/eligibility/runway-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Runway's own page on 2026-11-10.
synthetic: false
tags:
- Video Generation
- Image Generation
- Artificial Intelligence
- Machine Learning
- Generative AI
- Avatars
- Characters
- WebRTC
- Creative Tools
- Real-Time
---
