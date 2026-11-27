---
api_specs:
- filename: lumify-ai-admin-api-openapi.yml
  format: yaml
  label: lumify-ai Admin API
  slug: lumify-ai-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-admin-api-openapi.yml
- filename: lumify-ai-agent-api-openapi.yml
  format: yaml
  label: lumify-ai Agent API
  slug: lumify-ai-agent-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-agent-api-openapi.yml
- filename: lumify-ai-app-api-openapi.yml
  format: yaml
  label: lumify-ai App API
  slug: lumify-ai-app-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-app-api-openapi.yml
- filename: lumify-ai-auth-api-openapi.yml
  format: yaml
  label: lumify-ai Auth API
  slug: lumify-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-auth-api-openapi.yml
- filename: lumify-ai-events-api-openapi.yml
  format: yaml
  label: lumify-ai Events API
  slug: lumify-ai-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-events-api-openapi.yml
- filename: lumify-ai-grade-api-openapi.yml
  format: yaml
  label: lumify-ai Grade API
  slug: lumify-ai-grade-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-grade-api-openapi.yml
- filename: lumify-ai-health-api-openapi.yml
  format: yaml
  label: lumify-ai Health API
  slug: lumify-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-health-api-openapi.yml
- filename: lumify-ai-mcp-api-openapi.yml
  format: yaml
  label: lumify-ai MCP API
  slug: lumify-ai-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-mcp-api-openapi.yml
- filename: lumify-ai-oauth-api-openapi.yml
  format: yaml
  label: lumify-ai OAuth API
  slug: lumify-ai-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-oauth-api-openapi.yml
- filename: lumify-ai-players-api-openapi.yml
  format: yaml
  label: lumify-ai Players API
  slug: lumify-ai-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-players-api-openapi.yml
- filename: lumify-ai-public-api-openapi.yml
  format: yaml
  label: lumify-ai Public API
  slug: lumify-ai-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-public-api-openapi.yml
- filename: lumify-ai-resolve-api-openapi.yml
  format: yaml
  label: lumify-ai Resolve API
  slug: lumify-ai-resolve-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-resolve-api-openapi.yml
- filename: lumify-ai-sports-api-openapi.yml
  format: yaml
  label: lumify-ai Sports API
  slug: lumify-ai-sports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-sports-api-openapi.yml
- filename: lumify-ai-teams-api-openapi.yml
  format: yaml
  label: lumify-ai Teams API
  slug: lumify-ai-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-teams-api-openapi.yml
- filename: lumify-ai-trial-api-openapi.yml
  format: yaml
  label: lumify-ai Trial API
  slug: lumify-ai-trial-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-trial-api-openapi.yml
- filename: lumify-ai-webhooks-api-openapi.yml
  format: yaml
  label: lumify-ai Webhooks API
  slug: lumify-ai-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lumify-ai/openapi/lumify-ai-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least eighteen (18) years of age or the age of majority in your jurisdiction to use the Service.
    type: individual
  - text: If you register on behalf of a business or other legal entity, you represent that you have authority to bind that entity.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years of age or the age of majority in your jurisdiction to use the Service.
    value: '18'
  restricted_uses:
  - summary: Gambling and wagering
    text: Lumify is not a sportsbook, gambling operator, fantasy sports operator, or wagering platform. We do not accept wagers or facilitate gambling transactions.
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
name: lumify-ai
provenance_date: '2026-11-10'
provider_name: lumify-ai
provider_slug: lumify-ai
slug: lumify-ai-eligibility
source_date: '2026-11-10'
source_filename: lumify-ai-eligibility.yml
source_heading: Eligibility
source_page: https://lumify.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: lumify-ai\naid: lumify-ai\nurl: https://lumify.ai/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years of age or the age of majority in your jurisdiction to use the Service.\n- type: business\n  text: If you register on behalf of a business or other legal entity, you represent that you have authority to\n    bind that entity.\nrestricted_uses:\n- summary: Gambling and wagering\n  text: Lumify is not a sportsbook, gambling operator, fantasy sports operator, or wagering platform. We\
  \ do not\n    accept wagers or facilitate gambling transactions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years of age or the age of majority in your jurisdiction to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/lumify-ai/eligibility/lumify-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from lumify-ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sports
- Artificial Intelligence
- Real-Time
- Betting
---
