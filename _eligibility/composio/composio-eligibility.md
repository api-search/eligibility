---
api_specs:
- filename: composio-auth-configs-api-openapi.yml
  format: yaml
  label: Composio Auth Configs API
  slug: composio-auth-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-auth-configs-api-openapi.yml
- filename: composio-authentication-api-openapi.yml
  format: yaml
  label: Composio Authentication API
  slug: composio-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-authentication-api-openapi.yml
- filename: composio-cli-api-openapi.yml
  format: yaml
  label: Composio CLI API
  slug: composio-cli-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-cli-api-openapi.yml
- filename: composio-cli-authentication-api-openapi.yml
  format: yaml
  label: Composio CLI Authentication API
  slug: composio-cli-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-cli-authentication-api-openapi.yml
- filename: composio-connected-accounts-api-openapi.yml
  format: yaml
  label: Composio Connected Accounts API
  slug: composio-connected-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-connected-accounts-api-openapi.yml
- filename: composio-files-api-openapi.yml
  format: yaml
  label: Composio Files API
  slug: composio-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-files-api-openapi.yml
- filename: composio-logs-api-openapi.yml
  format: yaml
  label: Composio Logs API
  slug: composio-logs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-logs-api-openapi.yml
- filename: composio-mcp-api-openapi.yml
  format: yaml
  label: Composio MCP API
  slug: composio-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-mcp-api-openapi.yml
- filename: composio-migration-api-openapi.yml
  format: yaml
  label: Composio Migration API
  slug: composio-migration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-migration-api-openapi.yml
- filename: composio-organization-management-api-openapi.yml
  format: yaml
  label: Composio Organization Management API
  slug: composio-organization-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-organization-management-api-openapi.yml
- filename: composio-projects-api-openapi.yml
  format: yaml
  label: Composio Projects API
  slug: composio-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-projects-api-openapi.yml
- filename: composio-tool-router-api-openapi.yml
  format: yaml
  label: Composio Tool Router API
  slug: composio-tool-router-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-tool-router-api-openapi.yml
- filename: composio-toolkits-api-openapi.yml
  format: yaml
  label: Composio Toolkits API
  slug: composio-toolkits-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-toolkits-api-openapi.yml
- filename: composio-tools-api-openapi.yml
  format: yaml
  label: Composio Tools API
  slug: composio-tools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-tools-api-openapi.yml
- filename: composio-triggers-api-openapi.yml
  format: yaml
  label: Composio Triggers API
  slug: composio-triggers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-triggers-api-openapi.yml
- filename: composio-webhook-endpoints-api-openapi.yml
  format: yaml
  label: Composio Webhook Endpoints API
  slug: composio-webhook-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-webhook-endpoints-api-openapi.yml
- filename: composio-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: Composio Webhook Subscriptions API
  slug: composio-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/composio/openapi/composio-webhook-subscriptions-api-openapi.yml
claim_count: 1
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
  - summary: Lawful use only; no minors harm, spam, impersonation
    text: You agree to use the platform only for lawful purposes and in accordance with these Terms.
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
name: Composio
provenance_date: '2026-11-09'
provider_name: Composio
provider_slug: composio
slug: composio-eligibility
source_date: '2026-11-09'
source_filename: composio-eligibility.yml
source_heading: Eligibility
source_page: https://composio.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Composio\naid: composio\nurl: https://composio.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only; no minors harm, spam, impersonation\n  text: You agree to use the platform only for lawful purposes and in accordance with these Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/composio/eligibility/composio-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Composio's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Authentication
- Integration
- MCP
- OAuth
- Sandbox
- Tools
- Triggers
- Unified API
- Webhook
---
