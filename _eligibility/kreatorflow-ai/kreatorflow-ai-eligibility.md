---
api_specs:
- filename: kreatorflow-ai-audio-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Audio API
  slug: kreatorflow-ai-audio-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-audio-api-openapi.yml
- filename: kreatorflow-ai-images-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Images API
  slug: kreatorflow-ai-images-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-images-api-openapi.yml
- filename: kreatorflow-ai-jobs-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Jobs API
  slug: kreatorflow-ai-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-jobs-api-openapi.yml
- filename: kreatorflow-ai-lip-sync-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Lip Sync API
  slug: kreatorflow-ai-lip-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-lip-sync-api-openapi.yml
- filename: kreatorflow-ai-mcp-api-openapi.yml
  format: yaml
  label: kreatorflow-ai MCP API
  slug: kreatorflow-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-mcp-api-openapi.yml
- filename: kreatorflow-ai-models-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Models API
  slug: kreatorflow-ai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-models-api-openapi.yml
- filename: kreatorflow-ai-uploads-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Uploads API
  slug: kreatorflow-ai-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-uploads-api-openapi.yml
- filename: kreatorflow-ai-video-api-openapi.yml
  format: yaml
  label: kreatorflow-ai Video API
  slug: kreatorflow-ai-video-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kreatorflow-ai/openapi/kreatorflow-ai-video-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service for an organisation, you confirm that you are allowed to accept these Terms for it.
    type: business
  minimum_age:
    text: You must be 18 or over to use KreatorFlow .
    value: '18'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We ask for your date of birth when you sign up.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: kreatorflow-ai
provenance_date: '2026-11-09'
provider_name: kreatorflow-ai
provider_slug: kreatorflow-ai
slug: kreatorflow-ai-eligibility
source_date: '2026-11-09'
source_filename: kreatorflow-ai-eligibility.yml
source_heading: Eligibility
source_page: https://kreatorflow.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: kreatorflow-ai\naid: kreatorflow-ai\nurl: https://kreatorflow.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you use the Service for an organisation, you confirm that you are allowed to accept these Terms for it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We ask for your date of birth when you sign up.\nminimum_age:\n  value: '18'\n  text: You must be 18 or over to use KreatorFlow .\n"
source_yaml_url: https://artifacts.apis.io/kreatorflow-ai/eligibility/kreatorflow-ai-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from kreatorflow-ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Video
- Image
- Voice
- Platform
---
