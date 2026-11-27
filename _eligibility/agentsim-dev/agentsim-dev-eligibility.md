---
api_specs:
- filename: agentsim-dev-agents-api-openapi.yml
  format: yaml
  label: AgentSIM Agents API
  slug: agentsim-dev-agents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsim-dev/openapi/agentsim-dev-agents-api-openapi.yml
- filename: agentsim-dev-browser-access-api-openapi.yml
  format: yaml
  label: AgentSIM Browser Access API
  slug: agentsim-dev-browser-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsim-dev/openapi/agentsim-dev-browser-access-api-openapi.yml
- filename: agentsim-dev-sessions-api-openapi.yml
  format: yaml
  label: AgentSIM Sessions API
  slug: agentsim-dev-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agentsim-dev/openapi/agentsim-dev-sessions-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to register.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: Violate any applicable law or regulation
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
name: AgentSIM
provenance_date: '2026-11-09'
provider_name: AgentSIM
provider_slug: agentsim-dev
slug: agentsim-dev-eligibility
source_date: '2026-11-09'
source_filename: agentsim-dev-eligibility.yml
source_heading: Eligibility
source_page: https://agentsim.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentSIM\naid: agentsim-dev\nurl: https://agentsim.dev/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: Violate any applicable law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register.\n"
source_yaml_url: https://artifacts.apis.io/agentsim-dev/eligibility/agentsim-dev-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from AgentSIM's own page on 2026-11-09.
synthetic: false
tags:
- AgentSIM
- Authentication
- Identity
- Security
---
