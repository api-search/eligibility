---
api_specs:
- filename: configure-dev-auth-api-openapi.yml
  format: yaml
  label: Configure Auth API
  slug: configure-dev-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-auth-api-openapi.yml
- filename: configure-dev-connectors-api-openapi.yml
  format: yaml
  label: Configure Connectors API
  slug: configure-dev-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-connectors-api-openapi.yml
- filename: configure-dev-files-api-openapi.yml
  format: yaml
  label: Configure Files API
  slug: configure-dev-files-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-files-api-openapi.yml
- filename: configure-dev-import-api-openapi.yml
  format: yaml
  label: Configure Import API
  slug: configure-dev-import-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-import-api-openapi.yml
- filename: configure-dev-profile-api-openapi.yml
  format: yaml
  label: Configure Profile API
  slug: configure-dev-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-profile-api-openapi.yml
- filename: configure-dev-web-api-openapi.yml
  format: yaml
  label: Configure Web API
  slug: configure-dev-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-web-api-openapi.yml
- filename: configure-dev-webhooks-api-openapi.yml
  format: yaml
  label: Configure Webhooks API
  slug: configure-dev-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure-dev/openapi/configure-dev-webhooks-api-openapi.yml
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
  - summary: illegal use
    text: Use the service for any illegal purpose
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your account is identified by your verified phone number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Configure
provenance_date: '2026-11-09'
provider_name: Configure
provider_slug: configure-dev
slug: configure-dev-eligibility
source_date: '2026-11-09'
source_filename: configure-dev-eligibility.yml
source_heading: Eligibility
source_page: https://configure.dev/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Configure\naid: configure-dev\nurl: https://configure.dev/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: illegal use\n  text: Use the service for any illegal purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your account is identified by your verified phone number.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/configure-dev/eligibility/configure-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Configure's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Memory
- Personalization
- User Context
- MCP
---
