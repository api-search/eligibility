---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: (a) allow minors to access the Offerings or OpenSesame’s systems
    value: null
  restricted_uses:
  - summary: Minors access prohibited
    text: (a) allow minors to access the Offerings or OpenSesame’s systems
  - summary: Commercial business beyond internal training
    text: (2) conduct commercial business other than internal employee training and/or skills development
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
name: Opensesame
provenance_date: '2026-11-10'
provider_name: Opensesame
provider_slug: opensesame
slug: opensesame-eligibility
source_date: '2026-11-10'
source_filename: opensesame-eligibility.yml
source_heading: Eligibility
source_page: https://www.opensesame.com/legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Opensesame\naid: opensesame\nurl: https://www.opensesame.com/legal\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Minors access prohibited\n  text: (a) allow minors to access the Offerings or OpenSesame’s systems\n- summary: Commercial business beyond internal training\n  text: (2) conduct commercial business other than internal employee training and/or skills development\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: (a) allow minors to access the Offerings\
  \ or OpenSesame’s systems\n"
source_yaml_url: https://artifacts.apis.io/opensesame/eligibility/opensesame-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Opensesame's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Learning
- LMS
- Online Training
- Course Marketplace
- Corporate Training
- LMS Integration
- xAPI
- Applicative Saas
---
