---
api_specs:
- filename: chieflab-io-connectors-api-openapi.yml
  format: yaml
  label: ChiefLab Connectors API
  slug: chieflab-io-connectors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-connectors-api-openapi.yml
- filename: chieflab-io-gtm-api-openapi.yml
  format: yaml
  label: ChiefLab GTM API
  slug: chieflab-io-gtm-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-gtm-api-openapi.yml
- filename: chieflab-io-mcp-api-openapi.yml
  format: yaml
  label: ChiefLab MCP API
  slug: chieflab-io-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-mcp-api-openapi.yml
- filename: chieflab-io-public-api-openapi.yml
  format: yaml
  label: ChiefLab Public API
  slug: chieflab-io-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-public-api-openapi.yml
- filename: chieflab-io-runs-api-openapi.yml
  format: yaml
  label: ChiefLab Runs API
  slug: chieflab-io-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-runs-api-openapi.yml
- filename: chieflab-io-workspace-api-openapi.yml
  format: yaml
  label: ChiefLab Workspace API
  slug: chieflab-io-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chieflab-io/openapi/chieflab-io-workspace-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use ChiefLab if you are at least 16 years old and can lawfully enter into a binding agreement.
    type: individual
  minimum_age:
    text: You may use ChiefLab if you are at least 16 years old
    value: '16'
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
name: ChiefLab
provenance_date: '2026-11-09'
provider_name: ChiefLab
provider_slug: chieflab-io
slug: chieflab-io-eligibility
source_date: '2026-11-09'
source_filename: chieflab-io-eligibility.yml
source_heading: Eligibility
source_page: https://chieflab.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChiefLab\naid: chieflab-io\nurl: https://chieflab.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use ChiefLab if you are at least 16 years old and can lawfully enter into a binding agreement.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You may use ChiefLab if you are at least 16 years old\n"
source_yaml_url: https://artifacts.apis.io/chieflab-io/eligibility/chieflab-io-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from ChiefLab's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- Growth Marketing
- MCP
- Product Launch
- Marketing Automation
- Approval Workflows
- Developer Tools
---
