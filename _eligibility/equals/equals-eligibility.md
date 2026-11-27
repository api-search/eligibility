---
api_specs:
- filename: equals-memories-api-openapi.yml
  format: yaml
  label: Equals Memories API
  slug: equals-memories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/equals/openapi/equals-memories-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A EQUALS OR OTHER LEGAL ENTITY, YOU REPRESENT THAT YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re -export of the Platform
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
name: Equals
provenance_date: '2026-11-09'
provider_name: Equals
provider_slug: equals
slug: equals-eligibility
source_date: '2026-11-09'
source_filename: equals-eligibility.yml
source_heading: Eligibility
source_page: https://equals.com/policies/equals-online-terms-and-conditions-GP-april-11-22.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Equals\naid: equals\nurl: https://equals.com/policies/equals-online-terms-and-conditions-GP-april-11-22.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ARE ENTERING INTO THIS AGREEMENT ON BEHALF OF A EQUALS OR OTHER LEGAL ENTITY, YOU REPRESENT THAT\n    YOU HAVE THE AUTHORITY TO BIND SUCH ENTITY TO THIS AGREEMENT\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re -export of the Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/equals/eligibility/equals-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Equals's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Analytics
- Spreadsheets
- Business Intelligence
- Dashboards
- Data
- Revenue Operations
- Reporting
- MCP
- A2A
---
