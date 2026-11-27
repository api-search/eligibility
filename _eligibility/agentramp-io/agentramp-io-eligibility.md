---
claim_count: 1
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
  - summary: No harmful, deceptive, or illegal activity
    text: You may not use AgentRamp to build MCP servers that enable harmful, deceptive, or illegal activity.
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
name: agentramp-io
provenance_date: '2026-11-09'
provider_name: agentramp-io
provider_slug: agentramp-io
slug: agentramp-io-eligibility
source_date: '2026-11-09'
source_filename: agentramp-io-eligibility.yml
source_heading: Eligibility
source_page: https://agentramp.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agentramp-io\naid: agentramp-io\nurl: https://agentramp.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No harmful, deceptive, or illegal activity\n  text: You may not use AgentRamp to build MCP servers that enable harmful, deceptive, or illegal activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentramp-io/eligibility/agentramp-io-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from agentramp-io's own page on 2026-11-09.
synthetic: false
tags:
- Company
- MCP
- API Management
- Monitoring
- Proxy
- Developer Tools
---
