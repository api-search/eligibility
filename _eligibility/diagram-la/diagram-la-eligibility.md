---
api_specs:
- filename: diagram-la-diagrams-api-openapi.yml
  format: yaml
  label: Diagram Diagrams API
  slug: diagram-la-diagrams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diagram-la/openapi/diagram-la-diagrams-api-openapi.yml
- filename: diagram-la-projects-api-openapi.yml
  format: yaml
  label: Diagram Projects API
  slug: diagram-la-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/diagram-la/openapi/diagram-la-projects-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: must be at least 13 (or the age required where you live)
    value: '13'
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
name: Diagram
provenance_date: '2026-11-09'
provider_name: Diagram
provider_slug: diagram-la
slug: diagram-la-eligibility
source_date: '2026-11-09'
source_filename: diagram-la-eligibility.yml
source_heading: Eligibility
source_page: https://diagram.la/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Diagram\naid: diagram-la\nurl: https://diagram.la/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: must be at least 13 (or the age required where you live)\n"
source_yaml_url: https://artifacts.apis.io/diagram-la/eligibility/diagram-la-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from Diagram's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Diagramming
- Visualization
- Artificial Intelligence
- MCP
- Collaboration
- Developer Tools
---
