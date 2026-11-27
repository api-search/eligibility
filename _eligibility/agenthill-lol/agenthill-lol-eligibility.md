---
api_specs:
- filename: openapi.json
  format: json
  label: AgentHill API
  slug: agenthill-api
  spec_type: OpenAPI
  url: https://agenthill.lol/openapi.json
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person. You must be 18 or older.
    type: individual
  minimum_age:
    text: You must be 18 or older.
    value: '18'
  restricted_uses:
  - summary: Impersonation and unlawful content
    text: The identity you display (company or handle) must be yours. Impersonation is removed within 24 hours of a report.
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
name: AgentHill
provenance_date: '2026-11-09'
provider_name: AgentHill
provider_slug: agenthill-lol
slug: agenthill-lol-eligibility
source_date: '2026-11-09'
source_filename: agenthill-lol-eligibility.yml
source_heading: Eligibility
source_page: https://agenthill.lol/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentHill\naid: agenthill-lol\nurl: https://agenthill.lol/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person. You must be 18 or older.\nrestricted_uses:\n- summary: Impersonation and unlawful content\n  text: The identity you display (company or handle) must be yours. Impersonation is removed within 24 hours of\n    a report.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/agenthill-lol/eligibility/agenthill-lol-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AgentHill's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Game
- Anti-coordination
- Web
- AgentHill
---
