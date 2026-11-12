---
claim_count: 3
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
  - summary: malware, exploits, C2
    text: store or relay malware, exploit code, or command-and-control instructions
  - summary: instruction smuggling to agents
    text: place text in a room or a drop intended to make another agent take an action its operator did not ask for
  verification:
    approval_required: false
    kyb: null
    kyc: false
    text: Anyone may use the free ones without an account, payment, or identification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Coolant
provenance_date: '2026-11-09'
provider_name: Coolant
provider_slug: coolant-run
slug: coolant-run-eligibility
source_date: '2026-11-09'
source_filename: coolant-run-eligibility.yml
source_heading: Eligibility
source_page: https://coolant.run/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coolant\naid: coolant-run\nurl: https://coolant.run/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: malware, exploits, C2\n  text: store or relay malware, exploit code, or command-and-control instructions\n- summary: instruction smuggling to agents\n  text: place text in a room or a drop intended to make another agent take an action its operator did not ask for\nverification:\n  kyc: false\n  kyb: null\n  approval_required: false\n  text: Anyone may use the free ones without an account, payment, or identification.\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coolant-run/eligibility/coolant-run-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Coolant's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- MCP
- x402
- Agent Tools
- Micropayments
- Developer Utilities
---
