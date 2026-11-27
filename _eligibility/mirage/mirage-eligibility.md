---
api_specs:
- filename: mirage-audio-api-openapi.yml
  format: yaml
  label: Mirage Audio API
  slug: mirage-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mirage/openapi/mirage-audio-api-openapi.yml
- filename: mirage-health-api-openapi.yml
  format: yaml
  label: Mirage Health API
  slug: mirage-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mirage/openapi/mirage-health-api-openapi.yml
- filename: mirage-internal-api-openapi.yml
  format: yaml
  label: Mirage Internal API
  slug: mirage-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mirage/openapi/mirage-internal-api-openapi.yml
- filename: mirage-meta-text-overlays-api-openapi.yml
  format: yaml
  label: Mirage Meta Text Overlays API
  slug: mirage-meta-text-overlays-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mirage/openapi/mirage-meta-text-overlays-api-openapi.yml
- filename: mirage-root-api-openapi.yml
  format: yaml
  label: Mirage Root API
  slug: mirage-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mirage/openapi/mirage-root-api-openapi.yml
- filename: mirage-video-captions-api-openapi.yml
  format: yaml
  label: Mirage Video Captions API
  slug: mirage-video-captions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mirage/openapi/mirage-video-captions-api-openapi.yml
- filename: mirage-videos-api-openapi.yml
  format: yaml
  label: Mirage Videos API
  slug: mirage-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mirage/openapi/mirage-videos-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you can form a binding contract with Mirage (either on behalf of yourself or the entity you represent)
    type: individual
  - text: If you use the Services on behalf of an entity, organization, or company, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: you are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited use
    text: You agree not to use the Services, Mirage Content, or Output for any purpose that is unlawful or prohibited by these Terms or any Mirage policies
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
name: Mirage
provenance_date: '2026-11-10'
provider_name: Mirage
provider_slug: mirage
slug: mirage-eligibility
source_date: '2026-11-10'
source_filename: mirage-eligibility.yml
source_heading: Eligibility
source_page: https://mirage.app/legal/captions-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mirage\naid: mirage\nurl: https://mirage.app/legal/captions-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you can form a binding contract with Mirage (either on behalf of yourself\n    or the entity you represent)\n- type: business\n  text: If you use the Services on behalf of an entity, organization, or company, you represent and warrant that\n    you have the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Unlawful or prohibited use\n  text: You\
  \ agree not to use the Services, Mirage Content, or Output for any purpose that is unlawful or prohibited\n    by these Terms or any Mirage policies\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/mirage/eligibility/mirage-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mirage's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Video Generation
- Captions
- Media
- Content Creation
- Text-to-Speech
- Machine Learning
---
