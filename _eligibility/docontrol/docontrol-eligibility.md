---
api_specs:
- filename: docontrol-authentication-api-openapi.yml
  format: yaml
  label: DoControl Authentication API
  slug: docontrol-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docontrol/openapi/docontrol-authentication-api-openapi.yml
- filename: docontrol-graph-ql-api-openapi.yml
  format: yaml
  label: DoControl Graph QL API
  slug: docontrol-graph-ql-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/docontrol/openapi/docontrol-graph-ql-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: DoControl develops and operates a solution providing businesses a modern security layer
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
name: DoControl
provenance_date: '2026-11-09'
provider_name: DoControl
provider_slug: docontrol
slug: docontrol-eligibility
source_date: '2026-11-09'
source_filename: docontrol-eligibility.yml
source_heading: Eligibility
source_page: https://www.docontrol.io/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DoControl\naid: docontrol\nurl: https://www.docontrol.io/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: DoControl develops and operates a solution providing businesses a modern security layer\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/docontrol/eligibility/docontrol-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from DoControl's own page on 2026-11-09.
synthetic: false
tags:
- Data Security
- SaaS Security
- Data Access Governance
- Data Loss Prevention
- Insider Risk Management
- SSPM
- GraphQL
- MCP
---
