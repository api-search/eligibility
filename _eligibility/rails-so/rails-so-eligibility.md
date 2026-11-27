---
api_specs:
- filename: rails-so-api-openapi.json
  format: json
  label: Agent Rails public MCP and OAuth HTTP API API
  slug: agent-rails-public-mcp-and-oauth-http-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rails-so/openapi/_original/rails-so-api-openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person.
    type: individual
  minimum_age:
    text: You must be at least 13, or 16 in the EEA.
    value: '13'
  restricted_uses:
  - summary: Consequential decisions
    text: Do not use the apps to make consequential decisions about someone without the review and safeguards that decision requires.
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
name: rails-so
provenance_date: '2026-11-10'
provider_name: rails-so
provider_slug: rails-so
slug: rails-so-eligibility
source_date: '2026-11-10'
source_filename: rails-so-eligibility.yml
source_heading: Eligibility
source_page: https://rails.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: rails-so\naid: rails-so\nurl: https://rails.so/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person.\nrestricted_uses:\n- summary: Consequential decisions\n  text: Do not use the apps to make consequential decisions about someone without the review and safeguards that\n    decision requires.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13, or 16 in the EEA.\n"
source_yaml_url: https://artifacts.apis.io/rails-so/eligibility/rails-so-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from rails-so's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Productivity
- Collaboration
- ChatGPT
- Claude
- Company
---
