---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may use the Service only if ... in compliance with ... all applicable local, state, national, and international laws
  entity_types:
  - text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).
    type: individual
  minimum_age:
    text: you must be at least 18 years old (or the age of majority in your jurisdiction)
    value: '18'
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
name: exe.dev
provenance_date: '2026-11-09'
provider_name: exe.dev
provider_slug: exedev
slug: exedev-eligibility
source_date: '2026-11-09'
source_filename: exedev-eligibility.yml
source_heading: Eligibility
source_page: https://exe.dev/docs/terms-of-service.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: exe.dev\naid: exedev\nurl: https://exe.dev/docs/terms-of-service.md\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may use the Service only if ... in compliance with ... all applicable local, state, national, and international\n    laws\nentity_types:\n- type: individual\n  text: To use the Service, you must be at least 18 years old (or the age of majority in your jurisdiction).\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old (or the age of majority\
  \ in your jurisdiction)\n"
source_yaml_url: https://artifacts.apis.io/exedev/eligibility/exedev-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from exe.dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Cloud Computing
- Virtual Machines
- Sandbox
- AI Agents
- Infrastructure
- SSH
---
