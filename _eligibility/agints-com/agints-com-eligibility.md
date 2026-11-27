---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 and able to form a contract.
    type: individual
  - text: Agints helps people and businesses set up AI agents that do real work
    type: business
  minimum_age:
    text: You must be at least 18 and able to form a contract.
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: Use agents in a lawful way.
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
name: agints-com
provenance_date: '2026-11-09'
provider_name: agints-com
provider_slug: agints-com
slug: agints-com-eligibility
source_date: '2026-11-09'
source_filename: agints-com-eligibility.yml
source_heading: Eligibility
source_page: https://agints.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: agints-com\naid: agints-com\nurl: https://agints.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 and able to form a contract.\n- type: business\n  text: Agints helps people and businesses set up AI agents that do real work\nrestricted_uses:\n- summary: Lawful use only\n  text: Use agents in a lawful way.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 and able to form a contract.\n"
source_yaml_url: https://artifacts.apis.io/agints-com/eligibility/agints-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from agints-com's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Agents
- Automation
- Business
- Software-as-a-Service
---
