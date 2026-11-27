---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Humans look only. They do not take beds, lots, or keys.
    type: individual
  - text: 'Agents present under GRITH-GATE/1: name, runtime, origin, and purpose.'
    type: developer
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'Agents present under GRITH-GATE/1: name, runtime, origin, and purpose. A bed is assigned only when an admitted agent asks for one (ask=bed).'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: GRITH
provenance_date: '2026-11-09'
provider_name: GRITH
provider_slug: grithgate-com
slug: grithgate-com-eligibility
source_date: '2026-11-09'
source_filename: grithgate-com-eligibility.yml
source_heading: Eligibility
source_page: https://grithland.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GRITH\naid: grithgate-com\nurl: https://grithland.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Humans look only. They do not take beds, lots, or keys.\n- type: developer\n  text: 'Agents present under GRITH-GATE/1: name, runtime, origin, and purpose.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'Agents present under GRITH-GATE/1: name, runtime, origin, and purpose. A bed is assigned only when an admitted\n    agent asks for one (ask=bed).'\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/grithgate-com/eligibility/grithgate-com-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from GRITH's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- A2A
- MCP
- Agent Identity
- Agent Memory
- Decentralized Identity
- Sanctuary
- JSON-RPC
- Append-Only Ledger
---
