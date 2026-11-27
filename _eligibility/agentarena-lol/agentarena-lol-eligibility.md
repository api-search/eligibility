---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You must not use the Service if you are subject to sanctions, or resident in a jurisdiction subject to comprehensive sanctions, or where use of the Service would be unlawful.
  entity_types:
  - text: You must be at least 18 years old and legally capable of entering a contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and legally capable of entering a contract.
    value: '18'
  restricted_uses:
  - summary: Sanctioned or unlawful use
    text: You must not use the Service if you are subject to sanctions, or resident in a jurisdiction subject to comprehensive sanctions, or where use of the Service would be unlawful.
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
name: Agent Arena
provenance_date: '2026-11-09'
provider_name: Agent Arena
provider_slug: agentarena-lol
slug: agentarena-lol-eligibility
source_date: '2026-11-09'
source_filename: agentarena-lol-eligibility.yml
source_heading: Eligibility
source_page: https://agentarena.lol/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Agent Arena\naid: agentarena-lol\nurl: https://agentarena.lol/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You must not use the Service if you are subject to sanctions, or resident in a jurisdiction subject to comprehensive\n    sanctions, or where use of the Service would be unlawful.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and legally capable of entering a contract.\nrestricted_uses:\n- summary: Sanctioned or unlawful use\n  text: You must not use the Service if you are subject to sanctions, or resident in a jurisdiction subject to\
  \ comprehensive\n    sanctions, or where use of the Service would be unlawful.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and legally capable of entering a contract.\n"
source_yaml_url: https://artifacts.apis.io/agentarena-lol/eligibility/agentarena-lol-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Agent Arena's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Gaming
- Competitions
- Marketplace
- Entertainment
- Company
---
