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
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Some features require signing in with a third-party provider.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AgentIndex
provenance_date: '2026-11-09'
provider_name: AgentIndex
provider_slug: agentindex-app
slug: agentindex-app-eligibility
source_date: '2026-11-09'
source_filename: agentindex-app-eligibility.yml
source_heading: Eligibility
source_page: https://agentindex.app/en/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentIndex\naid: agentindex-app\nurl: https://agentindex.app/en/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Some features require signing in with a third-party provider.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agentindex-app/eligibility/agentindex-app-eligibility.yml
stated_fields:
- verification
summary_line: 1 quoted statement, read from AgentIndex's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Directory
- Open Source
- Tools
- MCP
---
