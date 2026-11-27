---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Create your account for yourself as an individual
    type: individual
  minimum_age:
    text: Are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Illegal or commercial use
    text: Use the services for illegal purposes
  - summary: Automated data collection
    text: Collect or list data on the users of our platform, in particular by means of algorithms.
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
name: Blindmate
provenance_date: '2026-11-09'
provider_name: Blindmate
provider_slug: blindmate
slug: blindmate-eligibility
source_date: '2026-11-09'
source_filename: blindmate-eligibility.yml
source_heading: Eligibility
source_page: https://blindmate.de/app-agb-en/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blindmate\naid: blindmate\nurl: https://blindmate.de/app-agb-en/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Create your account for yourself as an individual\nrestricted_uses:\n- summary: Illegal or commercial use\n  text: Use the services for illegal purposes\n- summary: Automated data collection\n  text: Collect or list data on the users of our platform, in particular by means of algorithms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Are at least 18\
  \ years old\n"
source_yaml_url: https://artifacts.apis.io/blindmate/eligibility/blindmate-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Blindmate's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Dating
- Social
- Matchmaking
- Mobile App
- Consumer
- Privacy
---
