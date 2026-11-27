---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: BrickTrack is intended for Australian residents. If you reside outside Australia, please do not use this service.
  entity_types:
  - text: You must be 18 or older to create an account.
    type: individual
  - text: 'Professional trial: firms get a trial period, which may be extended'
    type: business
  minimum_age:
    text: You must be 18 or older to create an account.
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
name: BrickTrack
provenance_date: '2026-11-09'
provider_name: BrickTrack
provider_slug: bricktrack-au
slug: bricktrack-au-eligibility
source_date: '2026-11-09'
source_filename: bricktrack-au-eligibility.yml
source_heading: Eligibility
source_page: https://www.bricktrack.au/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BrickTrack\naid: bricktrack-au\nurl: https://www.bricktrack.au/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: BrickTrack is intended for Australian residents. If you reside outside Australia, please do not use this\n    service.\nentity_types:\n- type: individual\n  text: You must be 18 or older to create an account.\n- type: business\n  text: 'Professional trial: firms get a trial period, which may be extended'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 or\
  \ older to create an account.\n"
source_yaml_url: https://artifacts.apis.io/bricktrack-au/eligibility/bricktrack-au-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from BrickTrack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Real Estate
- Property Management
- Investment
- Software-as-a-Service
---
