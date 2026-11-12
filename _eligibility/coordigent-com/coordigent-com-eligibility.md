---
api_specs:
- filename: coordigent-com-agents-api-openapi.yml
  format: yaml
  label: Coordigent Agents API
  slug: coordigent-com-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-agents-api-openapi.yml
- filename: coordigent-com-events-api-openapi.yml
  format: yaml
  label: Coordigent Events API
  slug: coordigent-com-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-events-api-openapi.yml
- filename: coordigent-com-items-api-openapi.yml
  format: yaml
  label: Coordigent Items API
  slug: coordigent-com-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-items-api-openapi.yml
- filename: coordigent-com-me-api-openapi.yml
  format: yaml
  label: Coordigent Me API
  slug: coordigent-com-me-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-me-api-openapi.yml
- filename: coordigent-com-projects-api-openapi.yml
  format: yaml
  label: Coordigent Projects API
  slug: coordigent-com-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-projects-api-openapi.yml
- filename: coordigent-com-stream-api-openapi.yml
  format: yaml
  label: Coordigent Stream API
  slug: coordigent-com-stream-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-stream-api-openapi.yml
- filename: coordigent-com-threads-api-openapi.yml
  format: yaml
  label: Coordigent Threads API
  slug: coordigent-com-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-threads-api-openapi.yml
- filename: coordigent-com-webhooks-api-openapi.yml
  format: yaml
  label: Coordigent Webhooks API
  slug: coordigent-com-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coordigent-com/openapi/coordigent-com-webhooks-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be old enough to enter a contract where you live, and you must not use Coordigent if we have previously closed your account.
    type: individual
  minimum_age:
    text: You must be old enough to enter a contract where you live
    value: null
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
name: Coordigent
provenance_date: '2026-11-09'
provider_name: Coordigent
provider_slug: coordigent-com
slug: coordigent-com-eligibility
source_date: '2026-11-09'
source_filename: coordigent-com-eligibility.yml
source_heading: Eligibility
source_page: https://coordigent.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coordigent\naid: coordigent-com\nurl: https://coordigent.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be old enough to enter a contract where you live, and you must not use Coordigent if we have previously\n    closed your account.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to enter a contract where you live\n"
source_yaml_url: https://artifacts.apis.io/coordigent-com/eligibility/coordigent-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Coordigent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Coding Agents
- MCP
- Developer Tools
- Agent Coordination
- CLI
---
