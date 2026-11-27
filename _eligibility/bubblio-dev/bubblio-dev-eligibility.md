---
api_specs:
- filename: bubblio-dev-agent-keys-api-openapi.yml
  format: yaml
  label: bubblio-dev Agent Keys API
  slug: bubblio-dev-agent-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-agent-keys-api-openapi.yml
- filename: bubblio-dev-approvals-api-openapi.yml
  format: yaml
  label: bubblio-dev Approvals API
  slug: bubblio-dev-approvals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-approvals-api-openapi.yml
- filename: bubblio-dev-discovery-api-openapi.yml
  format: yaml
  label: bubblio-dev Discovery API
  slug: bubblio-dev-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-discovery-api-openapi.yml
- filename: bubblio-dev-mcp-api-openapi.yml
  format: yaml
  label: bubblio-dev MCP API
  slug: bubblio-dev-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-mcp-api-openapi.yml
- filename: bubblio-dev-platform-push-api-openapi.yml
  format: yaml
  label: bubblio-dev Platform Push API
  slug: bubblio-dev-platform-push-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-platform-push-api-openapi.yml
- filename: bubblio-dev-platform-sync-api-openapi.yml
  format: yaml
  label: bubblio-dev Platform Sync API
  slug: bubblio-dev-platform-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/bubblio-dev/openapi/bubblio-dev-platform-sync-api-openapi.yml
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
  - summary: Regulated data
    text: don't route regulated data through it that it isn't built for (it answers questions and runs actions you declare — not a medical, legal, or financial adviser)
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: 'It is in private beta : accounts require approval, features evolve, and the service is provided as-is'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: bubblio-dev
provenance_date: '2026-11-09'
provider_name: bubblio-dev
provider_slug: bubblio-dev
slug: bubblio-dev-eligibility
source_date: '2026-11-09'
source_filename: bubblio-dev-eligibility.yml
source_heading: Eligibility
source_page: https://bubblio.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: bubblio-dev\naid: bubblio-dev\nurl: https://bubblio.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Regulated data\n  text: don't route regulated data through it that it isn't built for (it answers questions and runs actions you\n    declare — not a medical, legal, or financial adviser)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: 'It is in private beta : accounts require approval, features evolve, and the service is provided as-is'\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/bubblio-dev/eligibility/bubblio-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from bubblio-dev's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Payments
- Automation
- Platform
- Agents
---
