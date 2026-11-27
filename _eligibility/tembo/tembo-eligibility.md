---
api_specs:
- filename: tembo-agents-api-openapi.yml
  format: yaml
  label: Tembo Agents API
  slug: tembo-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-agents-api-openapi.yml
- filename: tembo-api-keys-api-openapi.yml
  format: yaml
  label: Tembo API Keys API
  slug: tembo-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-api-keys-api-openapi.yml
- filename: tembo-artifacts-api-openapi.yml
  format: yaml
  label: Tembo Artifacts API
  slug: tembo-artifacts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-artifacts-api-openapi.yml
- filename: tembo-authentication-api-openapi.yml
  format: yaml
  label: Tembo Authentication API
  slug: tembo-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-authentication-api-openapi.yml
- filename: tembo-billing-api-openapi.yml
  format: yaml
  label: Tembo Billing API
  slug: tembo-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-billing-api-openapi.yml
- filename: tembo-insights-api-openapi.yml
  format: yaml
  label: Tembo Insights API
  slug: tembo-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-insights-api-openapi.yml
- filename: tembo-integrations-api-openapi.yml
  format: yaml
  label: Tembo Integrations API
  slug: tembo-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-integrations-api-openapi.yml
- filename: tembo-mcp-connections-api-openapi.yml
  format: yaml
  label: Tembo MCP Connections API
  slug: tembo-mcp-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-mcp-connections-api-openapi.yml
- filename: tembo-messages-api-openapi.yml
  format: yaml
  label: Tembo Messages API
  slug: tembo-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-messages-api-openapi.yml
- filename: tembo-models-api-openapi.yml
  format: yaml
  label: Tembo Models API
  slug: tembo-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-models-api-openapi.yml
- filename: tembo-oauth-api-openapi.yml
  format: yaml
  label: Tembo OAuth API
  slug: tembo-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-oauth-api-openapi.yml
- filename: tembo-organizations-api-openapi.yml
  format: yaml
  label: Tembo Organizations API
  slug: tembo-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-organizations-api-openapi.yml
- filename: tembo-projects-api-openapi.yml
  format: yaml
  label: Tembo Projects API
  slug: tembo-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-projects-api-openapi.yml
- filename: tembo-pull-requests-api-openapi.yml
  format: yaml
  label: Tembo Pull requests API
  slug: tembo-pull-requests-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-pull-requests-api-openapi.yml
- filename: tembo-repositories-api-openapi.yml
  format: yaml
  label: Tembo Repositories API
  slug: tembo-repositories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-repositories-api-openapi.yml
- filename: tembo-runtimes-api-openapi.yml
  format: yaml
  label: Tembo Runtimes API
  slug: tembo-runtimes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-runtimes-api-openapi.yml
- filename: tembo-sessions-api-openapi.yml
  format: yaml
  label: Tembo Sessions API
  slug: tembo-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-sessions-api-openapi.yml
- filename: tembo-skills-api-openapi.yml
  format: yaml
  label: Tembo Skills API
  slug: tembo-skills-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-skills-api-openapi.yml
- filename: tembo-users-api-openapi.yml
  format: yaml
  label: Tembo Users API
  slug: tembo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tembo/openapi/tembo-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity or person accessing or using our Service
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High Risk Activities
    text: Use the Service with High Risk Activities;
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
name: Tembo
provenance_date: '2026-11-10'
provider_name: Tembo
provider_slug: tembo
slug: tembo-eligibility
source_date: '2026-11-10'
source_filename: tembo-eligibility.yml
source_heading: Eligibility
source_page: https://www.tembo.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tembo\naid: tembo\nurl: https://www.tembo.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: the entity or person accessing or using our Service\nrestricted_uses:\n- summary: High Risk Activities\n  text: Use the Service with High Risk Activities;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tembo/eligibility/tembo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Tembo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- AI Agents
- Coding Agents
- Developer Tools
- Sandbox
- MCP
- Automation
---
