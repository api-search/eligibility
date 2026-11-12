---
api_specs:
- filename: coderbuds-com-openapi-generated.yml
  format: yaml
  label: Coderbuds API
  slug: coderbuds-com-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/coderbuds-com/openapi/_ae-authored/coderbuds-com-openapi-generated.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old or have parental consent to use this service
    type: individual
  minimum_age:
    text: You must be at least 18 years old or have parental consent to use this service
    value: '18'
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
name: Coderbuds
provenance_date: '2026-11-09'
provider_name: Coderbuds
provider_slug: coderbuds-com
slug: coderbuds-com-eligibility
source_date: '2026-11-09'
source_filename: coderbuds-com-eligibility.yml
source_heading: Eligibility
source_page: https://coderbuds.com/docs/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coderbuds\naid: coderbuds-com\nurl: https://coderbuds.com/docs/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or have parental consent to use this service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or have parental consent to use this service\n"
source_yaml_url: https://artifacts.apis.io/coderbuds-com/eligibility/coderbuds-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Coderbuds's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DORA Metrics
- Engineering Metrics
- Developer Productivity
- Code Review
- AI Agents
- MCP
- Software Engineering Intelligence
---
