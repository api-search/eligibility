---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The service may not be used from, or for the benefit of anyone in, jurisdictions subject to comprehensive sanctions, or by anyone on an applicable sanctions list (including OFAC lists).
  entity_types:
  - text: You must be at least 18 years old (or the age of majority where you live) and able to form a binding contract to buy through AgentRoam.
    type: individual
  minimum_age:
    text: You must be at least 18 years old (or the age of majority where you live)
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions and persons
    text: The service may not be used from, or for the benefit of anyone in, jurisdictions subject to comprehensive sanctions, or by anyone on an applicable sanctions list (including OFAC lists).
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
name: AgentRoam.ai
provenance_date: '2026-11-09'
provider_name: AgentRoam.ai
provider_slug: agentroam-ai
slug: agentroam-ai-eligibility
source_date: '2026-11-09'
source_filename: agentroam-ai-eligibility.yml
source_heading: Eligibility
source_page: https://agentroam.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgentRoam.ai\naid: agentroam-ai\nurl: https://agentroam.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The service may not be used from, or for the benefit of anyone in, jurisdictions subject to comprehensive\n    sanctions, or by anyone on an applicable sanctions list (including OFAC lists).\nentity_types:\n- type: individual\n  text: You must be at least 18 years old (or the age of majority where you live) and able to form a binding contract\n    to buy through AgentRoam.\nrestricted_uses:\n- summary: Sanctioned jurisdictions and persons\n  text: The service may not be\
  \ used from, or for the benefit of anyone in, jurisdictions subject to comprehensive\n    sanctions, or by anyone on an applicable sanctions list (including OFAC lists).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old (or the age of majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/agentroam-ai/eligibility/agentroam-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from AgentRoam.ai's own page on 2026-11-09.
synthetic: false
tags:
- eSIM
- Travel Data
- AI Agents
- Mobile Connectivity
---
