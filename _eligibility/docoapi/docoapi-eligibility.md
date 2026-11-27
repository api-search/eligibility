---
api_specs:
- filename: docoapi-admin-api-openapi.yml
  format: yaml
  label: Saga Labs Admin API
  slug: docoapi-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-admin-api-openapi.yml
- filename: docoapi-auth-api-openapi.yml
  format: yaml
  label: Saga Labs Auth API
  slug: docoapi-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-auth-api-openapi.yml
- filename: docoapi-billing-api-openapi.yml
  format: yaml
  label: Saga Labs Billing API
  slug: docoapi-billing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-billing-api-openapi.yml
- filename: docoapi-github-api-openapi.yml
  format: yaml
  label: Saga Labs GitHub API
  slug: docoapi-github-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-github-api-openapi.yml
- filename: docoapi-health-api-openapi.yml
  format: yaml
  label: Saga Labs Health API
  slug: docoapi-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-health-api-openapi.yml
- filename: docoapi-mcp-api-openapi.yml
  format: yaml
  label: Saga Labs MCP API
  slug: docoapi-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-mcp-api-openapi.yml
- filename: docoapi-portal-api-openapi.yml
  format: yaml
  label: Saga Labs Portal API
  slug: docoapi-portal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-portal-api-openapi.yml
- filename: docoapi-portal-search-api-openapi.yml
  format: yaml
  label: Saga Labs Portal Search API
  slug: docoapi-portal-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-portal-search-api-openapi.yml
- filename: docoapi-projects-api-openapi.yml
  format: yaml
  label: Saga Labs Projects API
  slug: docoapi-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-projects-api-openapi.yml
- filename: docoapi-proxy-api-openapi.yml
  format: yaml
  label: Saga Labs Proxy API
  slug: docoapi-proxy-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-proxy-api-openapi.yml
- filename: docoapi-users-api-openapi.yml
  format: yaml
  label: Saga Labs Users API
  slug: docoapi-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-users-api-openapi.yml
- filename: docoapi-webhooks-api-openapi.yml
  format: yaml
  label: Saga Labs Webhooks API
  slug: docoapi-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-webhooks-api-openapi.yml
- filename: docoapi-workspaces-api-openapi.yml
  format: yaml
  label: Saga Labs Workspaces API
  slug: docoapi-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docoapi/openapi/docoapi-workspaces-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to create an account.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to create an account.
    value: '16'
  restricted_uses:
  - summary: Harassment or harm
    text: Use the service to harass, abuse, or harm others
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
name: Saga Labs
provenance_date: '2026-11-09'
provider_name: Saga Labs
provider_slug: docoapi
slug: docoapi-eligibility
source_date: '2026-11-09'
source_filename: docoapi-eligibility.yml
source_heading: Eligibility
source_page: https://docoapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Saga Labs\naid: docoapi\nurl: https://docoapi.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to create an account.\nrestricted_uses:\n- summary: Harassment or harm\n  text: Use the service to harass, abuse, or harm others\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/docoapi/eligibility/docoapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Saga Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- API Documentation
- Developer Tools
- Software-as-a-Service
- FastAPI
---
