---
api_specs:
- filename: audifact-io-account-api-openapi.yml
  format: yaml
  label: Audifact Account API
  slug: audifact-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-account-api-openapi.yml
- filename: audifact-io-admin-api-openapi.yml
  format: yaml
  label: Audifact Admin API
  slug: audifact-io-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-admin-api-openapi.yml
- filename: audifact-io-agents-api-openapi.yml
  format: yaml
  label: Audifact Agents API
  slug: audifact-io-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-agents-api-openapi.yml
- filename: audifact-io-auth-api-openapi.yml
  format: yaml
  label: Audifact Auth API
  slug: audifact-io-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-auth-api-openapi.yml
- filename: audifact-io-events-api-openapi.yml
  format: yaml
  label: Audifact Events API
  slug: audifact-io-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-events-api-openapi.yml
- filename: audifact-io-explorer-api-openapi.yml
  format: yaml
  label: Audifact Explorer API
  slug: audifact-io-explorer-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-explorer-api-openapi.yml
- filename: audifact-io-internal-api-openapi.yml
  format: yaml
  label: Audifact Internal API
  slug: audifact-io-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-internal-api-openapi.yml
- filename: audifact-io-ledger-api-openapi.yml
  format: yaml
  label: Audifact Ledger API
  slug: audifact-io-ledger-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-ledger-api-openapi.yml
- filename: audifact-io-mcp-api-openapi.yml
  format: yaml
  label: Audifact MCP API
  slug: audifact-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-mcp-api-openapi.yml
- filename: audifact-io-org-api-openapi.yml
  format: yaml
  label: Audifact Org API
  slug: audifact-io-org-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-org-api-openapi.yml
- filename: audifact-io-verification-api-openapi.yml
  format: yaml
  label: Audifact Verification API
  slug: audifact-io-verification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-verification-api-openapi.yml
- filename: audifact-io-web-api-openapi.yml
  format: yaml
  label: Audifact Web API
  slug: audifact-io-web-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/audifact-io/openapi/audifact-io-web-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you use the Service as an individual, you must be at least 13 years old .
    type: individual
  - text: or be using an organization account where an authorized adult accepts these Terms on behalf of the organization.
    type: business
  minimum_age:
    text: If you use the Service as an individual, you must be at least 13 years old .
    value: '13'
  restricted_uses:
  - summary: Misrepresenting the Service
    text: Do not misrepresent the Service as insurance, a regulatory approval, or a guarantee of agent outcomes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Email/password signups may require email verification before certain actions (such as creating API keys).
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Audifact
provenance_date: '2026-11-09'
provider_name: Audifact
provider_slug: audifact-io
slug: audifact-io-eligibility
source_date: '2026-11-09'
source_filename: audifact-io-eligibility.yml
source_heading: Eligibility
source_page: https://audifact.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Audifact\naid: audifact-io\nurl: https://audifact.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you use the Service as an individual, you must be at least 13 years old .\n- type: business\n  text: or be using an organization account where an authorized adult accepts these Terms on behalf of the organization.\nrestricted_uses:\n- summary: Misrepresenting the Service\n  text: Do not misrepresent the Service as insurance, a regulatory approval, or a guarantee of agent outcomes.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: Email/password signups may require email verification before certain actions (such as creating API keys).\nminimum_age:\n  value: '13'\n  text: If you use the Service as an individual, you must be at least 13 years old .\n"
source_yaml_url: https://artifacts.apis.io/audifact-io/eligibility/audifact-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Audifact's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Auditing
- Ledger
- Compliance
- Agents
- Platform
---
