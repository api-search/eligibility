---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If Customer or any Users are an agency, department, or other entity of the United States Government
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export compliance
    text: will not submit to the Services any information controlled under the U.S. International Traffic in Arms Regulations
  - summary: Harm to others
    text: use the Services to take any action that risks harm to others
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
name: Dome Systems
provenance_date: '2026-11-09'
provider_name: Dome Systems
provider_slug: dome-systems
slug: dome-systems-eligibility
source_date: '2026-11-09'
source_filename: dome-systems-eligibility.yml
source_heading: Eligibility
source_page: https://www.domesystems.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dome Systems\naid: dome-systems\nurl: https://www.domesystems.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: government\n  text: If Customer or any Users are an agency, department, or other entity of the United States Government\nrestricted_uses:\n- summary: Export compliance\n  text: will not submit to the Services any information controlled under the U.S. International Traffic in Arms\n    Regulations\n- summary: Harm to others\n  text: use the Services to take any action that risks harm to others\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dome-systems/eligibility/dome-systems-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Dome Systems's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI Agents
- Agent Governance
- AI Operations
- Authorization
- Audit
- MCP
- Enterprise
- Cedar Policy
- LLM
---
