---
api_specs:
- filename: superai-auth-api-openapi.yml
  format: yaml
  label: Super.ai Auth API
  slug: superai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-auth-api-openapi.yml
- filename: superai-files-api-openapi.yml
  format: yaml
  label: Super.ai Files API
  slug: superai-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-files-api-openapi.yml
- filename: superai-flow-executions-api-openapi.yml
  format: yaml
  label: Super.ai Flow Executions API
  slug: superai-flow-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-flow-executions-api-openapi.yml
- filename: superai-flows-api-openapi.yml
  format: yaml
  label: Super.ai Flows API
  slug: superai-flows-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-flows-api-openapi.yml
- filename: superai-human-review-tasks-api-openapi.yml
  format: yaml
  label: Super.ai Human Review Tasks API
  slug: superai-human-review-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-human-review-tasks-api-openapi.yml
- filename: superai-integrations-api-openapi.yml
  format: yaml
  label: Super.ai Integrations API
  slug: superai-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-integrations-api-openapi.yml
- filename: superai-models-api-openapi.yml
  format: yaml
  label: Super.ai Models API
  slug: superai-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-models-api-openapi.yml
- filename: superai-organizations-api-openapi.yml
  format: yaml
  label: Super.ai Organizations API
  slug: superai-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-organizations-api-openapi.yml
- filename: superai-plugins-api-openapi.yml
  format: yaml
  label: Super.ai Plugins API
  slug: superai-plugins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-plugins-api-openapi.yml
- filename: superai-profile-api-openapi.yml
  format: yaml
  label: Super.ai Profile API
  slug: superai-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-profile-api-openapi.yml
- filename: superai-service-accounts-api-openapi.yml
  format: yaml
  label: Super.ai Service Accounts API
  slug: superai-service-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-service-accounts-api-openapi.yml
- filename: superai-sso-api-openapi.yml
  format: yaml
  label: Super.ai SSO API
  slug: superai-sso-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-sso-api-openapi.yml
- filename: superai-task-data-api-openapi.yml
  format: yaml
  label: Super.ai Task Data API
  slug: superai-task-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-task-data-api-openapi.yml
- filename: superai-task-executions-api-openapi.yml
  format: yaml
  label: Super.ai Task Executions API
  slug: superai-task-executions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-task-executions-api-openapi.yml
- filename: superai-task-executors-api-openapi.yml
  format: yaml
  label: Super.ai Task Executors API
  slug: superai-task-executors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-task-executors-api-openapi.yml
- filename: superai-task-outputs-api-openapi.yml
  format: yaml
  label: Super.ai Task Outputs API
  slug: superai-task-outputs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-task-outputs-api-openapi.yml
- filename: superai-task-tags-api-openapi.yml
  format: yaml
  label: Super.ai Task Tags API
  slug: superai-task-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-task-tags-api-openapi.yml
- filename: superai-webhook-data-api-openapi.yml
  format: yaml
  label: Super.ai Webhook Data API
  slug: superai-webhook-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-webhook-data-api-openapi.yml
- filename: superai-worker-groups-api-openapi.yml
  format: yaml
  label: Super.ai Worker Groups API
  slug: superai-worker-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/superai/openapi/superai-worker-groups-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: High-risk activities
    text: THE PLATFORM AND THE RESULTS PROVIDED BY THE PLATFORM ARE NOT INTENDED FOR USE IN MISSION-CRITICAL SYSTEMS
  - summary: Investment and trading
    text: SUPER.AI IS NOT A BROKER AND IS NOT PROVIDING ANY INVESTMENT ADVICE
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
name: Super.ai
provenance_date: '2026-11-10'
provider_name: Super.ai
provider_slug: superai
slug: superai-eligibility
source_date: '2026-11-10'
source_filename: superai-eligibility.yml
source_heading: Eligibility
source_page: https://super.ai/terms_of_service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Super.ai\naid: superai\nurl: https://super.ai/terms_of_service.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk activities\n  text: THE PLATFORM AND THE RESULTS PROVIDED BY THE PLATFORM ARE NOT INTENDED FOR USE IN MISSION-CRITICAL SYSTEMS\n- summary: Investment and trading\n  text: SUPER.AI IS NOT A BROKER AND IS NOT PROVIDING ANY INVESTMENT ADVICE\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/superai/eligibility/superai-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from Super.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Ai Enterprise Software
- Intelligent Document Processing
- Document Processing
- Workflow Orchestration
- Automation
- Human-in-the-Loop
- Artificial Intelligence
- REST API
---
