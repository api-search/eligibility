---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Reliance on generated contracts
    text: You should consult qualified legal counsel in your jurisdiction before relying on, executing, or distributing any contract generated through the Service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: API keys are personal, non-transferable, and issued to a single email address.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ambr
provenance_date: '2026-11-09'
provider_name: Ambr
provider_slug: getamber-dev
slug: getamber-dev-eligibility
source_date: '2026-11-09'
source_filename: getamber-dev-eligibility.yml
source_heading: Eligibility
source_page: https://ambr.run/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ambr\naid: getamber-dev\nurl: https://ambr.run/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Reliance on generated contracts\n  text: You should consult qualified legal counsel in your jurisdiction before relying on, executing, or distributing\n    any contract generated through the Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: API keys are personal, non-transferable, and issued to a single email address.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/getamber-dev/eligibility/getamber-dev-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Ambr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Agentic Commerce
- Contracts
- Legal
- Ricardian Contracts
- Delegation
- Blockchain
- Base L2
- MCP
- A2A
- x402
- Agent-Native
---
