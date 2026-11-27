---
api_specs:
- filename: backrow-ai-chat-api-openapi.yml
  format: yaml
  label: Backrow Chat API
  slug: backrow-ai-chat-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-chat-api-openapi.yml
- filename: backrow-ai-credit-transactions-api-openapi.yml
  format: yaml
  label: Backrow Credit Transactions API
  slug: backrow-ai-credit-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-credit-transactions-api-openapi.yml
- filename: backrow-ai-diaries-api-openapi.yml
  format: yaml
  label: Backrow Diaries API
  slug: backrow-ai-diaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-diaries-api-openapi.yml
- filename: backrow-ai-documents-api-openapi.yml
  format: yaml
  label: Backrow Documents API
  slug: backrow-ai-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-documents-api-openapi.yml
- filename: backrow-ai-flashcards-api-openapi.yml
  format: yaml
  label: Backrow Flashcards API
  slug: backrow-ai-flashcards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-flashcards-api-openapi.yml
- filename: backrow-ai-health-api-openapi.yml
  format: yaml
  label: Backrow Health API
  slug: backrow-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-health-api-openapi.yml
- filename: backrow-ai-knowledge-state-api-openapi.yml
  format: yaml
  label: Backrow Knowledge State API
  slug: backrow-ai-knowledge-state-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-knowledge-state-api-openapi.yml
- filename: backrow-ai-lessons-api-openapi.yml
  format: yaml
  label: Backrow Lessons API
  slug: backrow-ai-lessons-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-lessons-api-openapi.yml
- filename: backrow-ai-match-video-api-openapi.yml
  format: yaml
  label: Backrow Match Video API
  slug: backrow-ai-match-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-match-video-api-openapi.yml
- filename: backrow-ai-notes-api-openapi.yml
  format: yaml
  label: Backrow Notes API
  slug: backrow-ai-notes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-notes-api-openapi.yml
- filename: backrow-ai-paths-api-openapi.yml
  format: yaml
  label: Backrow Paths API
  slug: backrow-ai-paths-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-paths-api-openapi.yml
- filename: backrow-ai-pricing-api-openapi.yml
  format: yaml
  label: Backrow Pricing API
  slug: backrow-ai-pricing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-pricing-api-openapi.yml
- filename: backrow-ai-profile-api-openapi.yml
  format: yaml
  label: Backrow Profile API
  slug: backrow-ai-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-profile-api-openapi.yml
- filename: backrow-ai-quizzes-api-openapi.yml
  format: yaml
  label: Backrow Quizzes API
  slug: backrow-ai-quizzes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-quizzes-api-openapi.yml
- filename: backrow-ai-recommendations-api-openapi.yml
  format: yaml
  label: Backrow Recommendations API
  slug: backrow-ai-recommendations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-recommendations-api-openapi.yml
- filename: backrow-ai-recordings-api-openapi.yml
  format: yaml
  label: Backrow Recordings API
  slug: backrow-ai-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-recordings-api-openapi.yml
- filename: backrow-ai-tools-api-openapi.yml
  format: yaml
  label: Backrow Tools API
  slug: backrow-ai-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-tools-api-openapi.yml
- filename: backrow-ai-webhooks-api-openapi.yml
  format: yaml
  label: Backrow Webhooks API
  slug: backrow-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/backrow-ai/openapi/backrow-ai-webhooks-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'By creating an account or using the Service, you affirm that: You are at least 13 years of age'
    type: individual
  minimum_age:
    text: The Service is not available to anyone under 13.
    value: '13'
  restricted_uses:
  - summary: Resale or sharing of access
    text: Share or resell access to the Service
  - summary: Competing products
    text: Use the Service to develop competing products
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We ask for your date of birth at sign up.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Backrow
provenance_date: '2026-11-09'
provider_name: Backrow
provider_slug: backrow-ai
slug: backrow-ai-eligibility
source_date: '2026-11-09'
source_filename: backrow-ai-eligibility.yml
source_heading: Eligibility
source_page: https://backrow.ai/legal/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Backrow\naid: backrow-ai\nurl: https://backrow.ai/legal/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'By creating an account or using the Service, you affirm that: You are at least 13 years of age'\nrestricted_uses:\n- summary: Resale or sharing of access\n  text: Share or resell access to the Service\n- summary: Competing products\n  text: Use the Service to develop competing products\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We ask for your date of birth at sign up.\nminimum_age:\n  value:\
  \ '13'\n  text: The Service is not available to anyone under 13.\n"
source_yaml_url: https://artifacts.apis.io/backrow-ai/eligibility/backrow-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Backrow's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Productivity
- Education
- Knowledge Management
- Software-as-a-Service
---
