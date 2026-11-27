---
api_specs:
- filename: burdenrateledger-com-dataset-api-openapi.yml
  format: yaml
  label: burdenrateledger-com Dataset API
  slug: burdenrateledger-com-dataset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/burdenrateledger-com/openapi/burdenrateledger-com-dataset-api-openapi.yml
- filename: burdenrateledger-com-mcp-api-openapi.yml
  format: yaml
  label: burdenrateledger-com MCP API
  slug: burdenrateledger-com-mcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/burdenrateledger-com/openapi/burdenrateledger-com-mcp-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Purchase is offered to people acting for purposes related to their trade or profession.
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
name: burdenrateledger-com
provenance_date: '2026-11-09'
provider_name: burdenrateledger-com
provider_slug: burdenrateledger-com
slug: burdenrateledger-com-eligibility
source_date: '2026-11-09'
source_filename: burdenrateledger-com-eligibility.yml
source_heading: Eligibility
source_page: https://burdenrateledger.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: burdenrateledger-com\naid: burdenrateledger-com\nurl: https://burdenrateledger.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Purchase is offered to people acting for purposes related to their trade or profession.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/burdenrateledger-com/eligibility/burdenrateledger-com-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from burdenrateledger-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Labor
- Calculator
- Small Business
---
