---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the people and companies (“Users” or “you”) that access and use our website
    type: individual
  - text: the people and companies (“Users” or “you”) that access and use our website
    type: business
  minimum_age:
    text: Users under the age of 18 are only permitted to access and use the Website while under the direct supervision of a parent or guardian.
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
name: vlt
provenance_date: '2026-11-10'
provider_name: vlt
provider_slug: vlt
slug: vlt-eligibility
source_date: '2026-11-10'
source_filename: vlt-eligibility.yml
source_heading: Eligibility
source_page: https://www.vlt.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: vlt\naid: vlt\nurl: https://www.vlt.io/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: the people and companies (“Users” or “you”) that access and use our website\n- type: business\n  text: the people and companies (“Users” or “you”) that access and use our website\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users under the age of 18 are only permitted to access and use the Website while under the direct supervision\n    of a parent\
  \ or guardian.\n"
source_yaml_url: https://artifacts.apis.io/vlt/eligibility/vlt-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from vlt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- JavaScript
- Package Management
- Package Registry
- Developer Tools
- CLI
- Serverless
- npm
- Dependency Management
- Open Source
---
