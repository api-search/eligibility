---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: CoreLoop is a service for businesses. You may use it only in the course of a business, trade, craft or profession.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use in breach of law
    text: use CoreLoop in breach of any applicable law, including sanctions, export control, consumer-protection, advertising and data-protection law.
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
name: CoreLoop
provenance_date: '2026-11-09'
provider_name: CoreLoop
provider_slug: coreloop-so
slug: coreloop-so-eligibility
source_date: '2026-11-09'
source_filename: coreloop-so-eligibility.yml
source_heading: Eligibility
source_page: https://coreloop.so/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CoreLoop\naid: coreloop-so\nurl: https://coreloop.so/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: CoreLoop is a service for businesses. You may use it only in the course of a business, trade, craft or profession.\nrestricted_uses:\n- summary: Use in breach of law\n  text: use CoreLoop in breach of any applicable law, including sanctions, export control, consumer-protection,\n    advertising and data-protection law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/coreloop-so/eligibility/coreloop-so-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CoreLoop's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- MCP
- A2A
- llms.txt
- Business Directory
- Agent Discoverability
---
