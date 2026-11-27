---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be of the legal age of majority in your country of residence.
    value: '18'
  restricted_uses:
  - summary: Offensive or harassing content
    text: transmitting or communicating any material or content which, in the sole and exclusive discretion of GOALS, is believed or deemed offensive
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
name: Goals
provenance_date: '2026-11-09'
provider_name: Goals
provider_slug: goals
slug: goals-eligibility
source_date: '2026-11-09'
source_filename: goals-eligibility.yml
source_heading: Eligibility
source_page: https://playgoals.com/en/eula
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Goals\naid: goals\nurl: https://playgoals.com/en/eula\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Offensive or harassing content\n  text: transmitting or communicating any material or content which, in the sole and exclusive discretion of GOALS,\n    is believed or deemed offensive\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be of the legal age of majority in your country of residence.\n"
source_yaml_url: https://artifacts.apis.io/goals/eligibility/goals-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Goals's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Gaming
- Video Game
- Football
- Esports
- Sports
---
