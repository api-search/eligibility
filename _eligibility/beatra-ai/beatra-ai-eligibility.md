---
api_specs:
- filename: beatra-ai-account-api-openapi.yml
  format: yaml
  label: Beatra AI Account API
  slug: beatra-ai-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-account-api-openapi.yml
- filename: beatra-ai-account-feedback-api-openapi.yml
  format: yaml
  label: Beatra AI Account Feedback API
  slug: beatra-ai-account-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-account-feedback-api-openapi.yml
- filename: beatra-ai-audio-api-openapi.yml
  format: yaml
  label: Beatra AI Audio API
  slug: beatra-ai-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-audio-api-openapi.yml
- filename: beatra-ai-catalog-api-openapi.yml
  format: yaml
  label: Beatra AI Catalog API
  slug: beatra-ai-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-catalog-api-openapi.yml
- filename: beatra-ai-health-api-openapi.yml
  format: yaml
  label: Beatra AI Health API
  slug: beatra-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-health-api-openapi.yml
- filename: beatra-ai-images-api-openapi.yml
  format: yaml
  label: Beatra AI Images API
  slug: beatra-ai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-images-api-openapi.yml
- filename: beatra-ai-mcp-device-authorization-api-openapi.yml
  format: yaml
  label: Beatra AI MCP Device Authorization API
  slug: beatra-ai-mcp-device-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-mcp-device-authorization-api-openapi.yml
- filename: beatra-ai-music-api-openapi.yml
  format: yaml
  label: Beatra AI Music API
  slug: beatra-ai-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-music-api-openapi.yml
- filename: beatra-ai-payments-api-openapi.yml
  format: yaml
  label: Beatra AI Payments API
  slug: beatra-ai-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-payments-api-openapi.yml
- filename: beatra-ai-tasks-api-openapi.yml
  format: yaml
  label: Beatra AI Tasks API
  slug: beatra-ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-tasks-api-openapi.yml
- filename: beatra-ai-uploads-api-openapi.yml
  format: yaml
  label: Beatra AI Uploads API
  slug: beatra-ai-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-uploads-api-openapi.yml
- filename: beatra-ai-videos-api-openapi.yml
  format: yaml
  label: Beatra AI Videos API
  slug: beatra-ai-videos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-videos-api-openapi.yml
- filename: beatra-ai-voices-api-openapi.yml
  format: yaml
  label: Beatra AI Voices API
  slug: beatra-ai-voices-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-voices-api-openapi.yml
- filename: beatra-ai-webhooks-api-openapi.yml
  format: yaml
  label: Beatra AI Webhooks API
  slug: beatra-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-webhooks-api-openapi.yml
- filename: beatra-ai-chat-completions-api-openapi.yml
  format: yaml
  label: Beatra AI Chat Completions API
  slug: beatra-ai-chat-completions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatra-ai/openapi/beatra-ai-chat-completions-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and have full legal capacity to use the Service.
    type: individual
  - text: If you accept these Terms on behalf of a company or other organization, you represent that you are authorized to bind it
    type: business
  minimum_age:
    text: You must be at least 18 years old and have full legal capacity to use the Service.
    value: '18'
  restricted_uses:
  - summary: Deepfakes and impersonation
    text: impersonate real people or fabricate their words or actions without consent (deepfakes)
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
name: Beatra AI
provenance_date: '2026-11-09'
provider_name: Beatra AI
provider_slug: beatra-ai
slug: beatra-ai-eligibility
source_date: '2026-11-09'
source_filename: beatra-ai-eligibility.yml
source_heading: Eligibility
source_page: https://beatra.ai/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beatra AI\naid: beatra-ai\nurl: https://beatra.ai/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and have full legal capacity to use the Service.\n- type: business\n  text: If you accept these Terms on behalf of a company or other organization, you represent that you are authorized\n    to bind it\nrestricted_uses:\n- summary: Deepfakes and impersonation\n  text: impersonate real people or fabricate their words or actions without consent (deepfakes)\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and have full legal capacity to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/beatra-ai/eligibility/beatra-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beatra AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Multi-Modal
- Generation
- Social Data
---
