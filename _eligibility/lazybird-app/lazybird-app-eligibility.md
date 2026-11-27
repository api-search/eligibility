---
api_specs:
- filename: lazybird-app-auth-api-openapi.yml
  format: yaml
  label: Lazybird Auth API
  slug: lazybird-app-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-auth-api-openapi.yml
- filename: lazybird-app-checkout-api-openapi.yml
  format: yaml
  label: Lazybird Checkout API
  slug: lazybird-app-checkout-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-checkout-api-openapi.yml
- filename: lazybird-app-generate-speech-api-openapi.yml
  format: yaml
  label: Lazybird Generate Speech API
  slug: lazybird-app-generate-speech-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-generate-speech-api-openapi.yml
- filename: lazybird-app-me-api-openapi.yml
  format: yaml
  label: Lazybird Me API
  slug: lazybird-app-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-me-api-openapi.yml
- filename: lazybird-app-music-api-openapi.yml
  format: yaml
  label: Lazybird Music API
  slug: lazybird-app-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-music-api-openapi.yml
- filename: lazybird-app-projects-api-openapi.yml
  format: yaml
  label: Lazybird Projects API
  slug: lazybird-app-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-projects-api-openapi.yml
- filename: lazybird-app-status-api-openapi.yml
  format: yaml
  label: Lazybird Status API
  slug: lazybird-app-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-status-api-openapi.yml
- filename: lazybird-app-stock-api-openapi.yml
  format: yaml
  label: Lazybird Stock API
  slug: lazybird-app-stock-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-stock-api-openapi.yml
- filename: lazybird-app-voices-api-openapi.yml
  format: yaml
  label: Lazybird Voices API
  slug: lazybird-app-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lazybird-app/openapi/lazybird-app-voices-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Services for a company or other organization, you agree on its behalf and confirm you're authorized to do so.
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Services.
    value: '16'
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
name: lazybird-app
provenance_date: '2026-11-09'
provider_name: Lazybird
provider_slug: lazybird-app
slug: lazybird-app-eligibility
source_date: '2026-11-09'
source_filename: lazybird-app-eligibility.yml
source_heading: Eligibility
source_page: https://www.lazybird.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: lazybird-app\naid: lazybird-app\nurl: https://www.lazybird.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Services for a company or other organization, you agree on its behalf and confirm you're\n    authorized to do so.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/lazybird-app/eligibility/lazybird-app-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from lazybird-app's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Voiceover
- Text-to-Speech
- Creator Tools
- Multilingual
---
