---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Assembly provides registered organizations a peer to peer recognition system (the "Service").
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Suspended or removed users
    text: The Assembly service is not available to any users suspended or removed from the system by Assembly for any reason.
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
name: Assembly
provenance_date: '2026-11-09'
provider_name: Assembly
provider_slug: assembly
slug: assembly-eligibility
source_date: '2026-11-09'
source_filename: assembly-eligibility.yml
source_heading: Eligibility
source_page: https://joinassembly.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Assembly\naid: assembly\nurl: https://joinassembly.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Assembly provides registered organizations a peer to peer recognition system (the \"Service\").\nrestricted_uses:\n- summary: Suspended or removed users\n  text: The Assembly service is not available to any users suspended or removed from the system by Assembly for\n    any reason.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/assembly/eligibility/assembly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Assembly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- Employee Recognition
- Employee Engagement
- Rewards
- Human Resources
- Workplace
- Software-as-a-Service
- Integration
- Loyalty & Incentives
---
