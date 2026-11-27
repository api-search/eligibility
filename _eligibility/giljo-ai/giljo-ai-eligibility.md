---
api_specs:
- filename: giljo-ai-account-deletion-api-openapi.yml
  format: yaml
  label: giljo-ai Account Deletion API
  slug: giljo-ai-account-deletion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-account-deletion-api-openapi.yml
- filename: giljo-ai-account-lifecycle-api-openapi.yml
  format: yaml
  label: giljo-ai Account Lifecycle API
  slug: giljo-ai-account-lifecycle-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-account-lifecycle-api-openapi.yml
- filename: giljo-ai-auth-api-openapi.yml
  format: yaml
  label: giljo-ai Auth API
  slug: giljo-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-auth-api-openapi.yml
- filename: giljo-ai-comm-threads-api-openapi.yml
  format: yaml
  label: giljo-ai Comm Threads API
  slug: giljo-ai-comm-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-comm-threads-api-openapi.yml
- filename: giljo-ai-connected-accounts-api-openapi.yml
  format: yaml
  label: giljo-ai Connected Accounts API
  slug: giljo-ai-connected-accounts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-connected-accounts-api-openapi.yml
- filename: giljo-ai-health-api-openapi.yml
  format: yaml
  label: giljo-ai Health API
  slug: giljo-ai-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-health-api-openapi.yml
- filename: giljo-ai-legal-api-openapi.yml
  format: yaml
  label: giljo-ai Legal API
  slug: giljo-ai-legal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-legal-api-openapi.yml
- filename: giljo-ai-oauth-api-openapi.yml
  format: yaml
  label: giljo-ai OAuth API
  slug: giljo-ai-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-oauth-api-openapi.yml
- filename: giljo-ai-oauth-dcr-api-openapi.yml
  format: yaml
  label: giljo-ai OAUTH Dcr API
  slug: giljo-ai-oauth-dcr-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-oauth-dcr-api-openapi.yml
- filename: giljo-ai-social-login-api-openapi.yml
  format: yaml
  label: giljo-ai Social Login API
  slug: giljo-ai-social-login-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-social-login-api-openapi.yml
- filename: giljo-ai-task-statuses-api-openapi.yml
  format: yaml
  label: giljo-ai Task Statuses API
  slug: giljo-ai-task-statuses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-task-statuses-api-openapi.yml
- filename: giljo-ai-tasks-api-openapi.yml
  format: yaml
  label: giljo-ai Tasks API
  slug: giljo-ai-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-tasks-api-openapi.yml
- filename: giljo-ai-users-api-openapi.yml
  format: yaml
  label: giljo-ai Users API
  slug: giljo-ai-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/giljo-ai/openapi/giljo-ai-users-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a binding contract to create an account.
    type: individual
  - text: If you use the service on behalf of a company or other entity, you represent that you have authority to bind that entity
    type: business
  minimum_age:
    text: You must be at least 18 years old and able to form a binding contract to create an account.
    value: '18'
  restricted_uses:
  - summary: Hosted service resale
    text: Resell, sublicense, or provide the hosted service to third parties as a service bureau or managed offering
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
name: giljo-ai
provenance_date: '2026-11-09'
provider_name: giljo-ai
provider_slug: giljo-ai
slug: giljo-ai-eligibility
source_date: '2026-11-09'
source_filename: giljo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://giljo.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: giljo-ai\naid: giljo-ai\nurl: https://giljo.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a binding contract to create an account.\n- type: business\n  text: If you use the service on behalf of a company or other entity, you represent that you have authority to\n    bind that entity\nrestricted_uses:\n- summary: Hosted service resale\n  text: Resell, sublicense, or provide the hosted service to third parties as a service bureau or managed offering\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a binding contract to create an account.\n"
source_yaml_url: https://artifacts.apis.io/giljo-ai/eligibility/giljo-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from giljo-ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Agents
- Collaboration
- Platform
---
