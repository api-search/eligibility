---
api_specs:
- filename: magichour-audio-projects-api-openapi.yml
  format: yaml
  label: Magic Hour Audio Projects API
  slug: magichour-audio-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/magichour/openapi/magichour-audio-projects-api-openapi.yml
- filename: magichour-files-api-openapi.yml
  format: yaml
  label: Magic Hour Files API
  slug: magichour-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/magichour/openapi/magichour-files-api-openapi.yml
- filename: magichour-image-projects-api-openapi.yml
  format: yaml
  label: Magic Hour Image Projects API
  slug: magichour-image-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/magichour/openapi/magichour-image-projects-api-openapi.yml
- filename: magichour-video-projects-api-openapi.yml
  format: yaml
  label: Magic Hour Video Projects API
  slug: magichour-video-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/magichour/openapi/magichour-video-projects-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be 18 years or older and able to form a binding contract with Magic Hour to use the Platform.
    type: individual
  minimum_age:
    text: You must be 18 years or older and able to form a binding contract with Magic Hour to use the Platform.
    value: '18'
  restricted_uses:
  - summary: Adult, gore or abusive content
    text: use the Platform to create adult content, gore, abusive, harmful, or disturbing;
  - summary: Sexual content involving minors or non-consensual intimate content
    text: You will not create, upload, or request any sexual content involving minors. You will not create or upload sexually explicit or intimate content of a real person without their consent, including AI-generated or altered likenesses.
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
name: Magic Hour
provenance_date: '2026-11-10'
provider_name: Magic Hour
provider_slug: magichour
slug: magichour-eligibility
source_date: '2026-11-10'
source_filename: magichour-eligibility.yml
source_heading: Eligibility
source_page: https://magichour.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Magic Hour\naid: magichour\nurl: https://magichour.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be 18 years or older and able to form a binding contract with Magic Hour to use the Platform.\nrestricted_uses:\n- summary: Adult, gore or abusive content\n  text: use the Platform to create adult content, gore, abusive, harmful, or disturbing;\n- summary: Sexual content involving minors or non-consensual intimate content\n  text: You will not create, upload, or request any sexual content involving minors.\
  \ You will not create or upload\n    sexually explicit or intimate content of a real person without their consent, including AI-generated or altered\n    likenesses.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older and able to form a binding contract with Magic Hour to use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/magichour/eligibility/magichour-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Magic Hour's own page on 2026-11-10.
synthetic: false
tags:
- AI Video
- Image Generation
- Audio
- Generative AI
- Voice Cloning
- Video Generation
- A2A
---
