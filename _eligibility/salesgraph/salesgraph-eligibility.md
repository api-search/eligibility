---
api_specs:
- filename: salesgraph-audit-api-openapi.yml
  format: yaml
  label: Salesgraph Audit API
  slug: salesgraph-audit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-audit-api-openapi.yml
- filename: salesgraph-commands-api-openapi.yml
  format: yaml
  label: Salesgraph Commands API
  slug: salesgraph-commands-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-commands-api-openapi.yml
- filename: salesgraph-runs-api-openapi.yml
  format: yaml
  label: Salesgraph Runs API
  slug: salesgraph-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-runs-api-openapi.yml
- filename: salesgraph-oms-api-openapi.yml
  format: yaml
  label: Salesgraph OMS API
  slug: salesgraph-oms-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-oms-api-openapi.yml
- filename: salesgraph-status-api-openapi.yml
  format: yaml
  label: Salesgraph Status API
  slug: salesgraph-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/salesgraph/openapi/salesgraph-status-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the service on behalf of a company or other entity, you represent that you have authority to bind that entity to these terms.
    type: business
  minimum_age:
    text: null
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
name: Salesgraph
provenance_date: '2026-11-10'
provider_name: Salesgraph
provider_slug: salesgraph
slug: salesgraph-eligibility
source_date: '2026-11-10'
source_filename: salesgraph-eligibility.yml
source_heading: Eligibility
source_page: https://salesgraph.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Salesgraph\naid: salesgraph\nurl: https://salesgraph.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the service on behalf of a company or other entity, you represent that you have authority\n    to bind that entity to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/salesgraph/eligibility/salesgraph-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Salesgraph's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Sales
- Revenue Automation
- Go-To-Market
- AI Agents
- MCP
- Sales Intelligence
- Competitive Intelligence
- Research
- Enterprise Sales
- A2A
---
