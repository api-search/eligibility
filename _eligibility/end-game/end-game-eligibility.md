---
api_specs:
- filename: end-game-threads-api-openapi.yml
  format: yaml
  label: Endgame Threads API
  slug: end-game-threads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/end-game/openapi/end-game-threads-api-openapi.yml
- filename: end-game-internal-api-openapi.yml
  format: yaml
  label: Endgame Internal API
  slug: end-game-internal-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/end-game/openapi/end-game-internal-api-openapi.yml
- filename: end-game-protected-static-api-openapi.yml
  format: yaml
  label: Endgame Protected Static API
  slug: end-game-protected-static-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/end-game/openapi/end-game-protected-static-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: the Customer signatory is of legal age to form a binding contract with Endgame
    value: legal age
  restricted_uses:
  - summary: Lawful use only
    text: (vi) use the Services in a way that violates any applicable laws, rules, or regulations.
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
name: Endgame
provenance_date: '2026-11-09'
provider_name: Endgame
provider_slug: end-game
slug: end-game-eligibility
source_date: '2026-11-09'
source_filename: end-game-eligibility.yml
source_heading: Eligibility
source_page: https://www.endgame.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Endgame\naid: end-game\nurl: https://www.endgame.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Lawful use only\n  text: (vi) use the Services in a way that violates any applicable laws, rules, or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: legal age\n  text: the Customer signatory is of legal age to form a binding contract with Endgame\n"
source_yaml_url: https://artifacts.apis.io/end-game/eligibility/end-game-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Endgame's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sales
- Revenue Intelligence
- Go-To-Market
- Artificial Intelligence
- Agents
- MCP
- Knowledge Graph
- CRM
- Conversation Intelligence
- A2A
---
