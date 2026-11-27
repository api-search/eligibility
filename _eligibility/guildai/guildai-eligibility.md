---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are joining one of your employer’s workspaces (“ Workspaces ”), for example, Customer is your employer.
    type: business
  - text: You represent that you are over the legal age and are the intended recipient of Customer’s invitation to the Services.
    type: individual
  minimum_age:
    text: the Services are not intended for and should not be used by (a) anyone under the age of eighteen
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
name: Guild.ai
provenance_date: '2026-11-09'
provider_name: Guild.ai
provider_slug: guildai
slug: guildai-eligibility
source_date: '2026-11-09'
source_filename: guildai-eligibility.yml
source_heading: Eligibility
source_page: https://www.guild.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Guild.ai\naid: guildai\nurl: https://www.guild.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are joining one of your employer’s workspaces (“ Workspaces ”), for example, Customer is your employer.\n- type: individual\n  text: You represent that you are over the legal age and are the intended recipient of Customer’s invitation to\n    the Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Services are not intended\
  \ for and should not be used by (a) anyone under the age of eighteen\n"
source_yaml_url: https://artifacts.apis.io/guildai/eligibility/guildai-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Guild.ai's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- AI Agents
- Agent Control Plane
- Agent Runtime
- Developer Tools
- MCP
- LLM
- Agent Governance
- SDK
- CLI
---
