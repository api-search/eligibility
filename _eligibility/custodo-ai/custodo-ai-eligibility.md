---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Custodo è un servizio destinato esclusivamente a imprese, professionisti ed enti che agiscono nell’esercizio della propria attività.
    type: business
  - text: 'Non è offerto a consumatori: la registrazione richiede una partita IVA valida.'
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Custodo
provenance_date: '2026-11-09'
provider_name: Custodo
provider_slug: custodo-ai
slug: custodo-ai-eligibility
source_date: '2026-11-09'
source_filename: custodo-ai-eligibility.yml
source_heading: Eligibility
source_page: https://custodo.ai/termini
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Custodo\naid: custodo-ai\nurl: https://custodo.ai/termini\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Custodo è un servizio destinato esclusivamente a imprese, professionisti ed enti che agiscono nell’esercizio\n    della propria attività.\n- type: individual\n  text: 'Non è offerto a consumatori: la registrazione richiede una partita IVA valida.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/custodo-ai/eligibility/custodo-ai-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Custodo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Document Management
- Business Management
- Small Business
- Digital Preservation
- E-Signature
- CRM
- Expense Management
- Time and Attendance
- AI Assistant
- MCP
- Italy
---
