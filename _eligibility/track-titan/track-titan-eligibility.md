---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use this Website.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use this Website.
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
name: Track Titan
provenance_date: '2026-11-10'
provider_name: Track Titan
provider_slug: track-titan
slug: track-titan-eligibility
source_date: '2026-11-10'
source_filename: track-titan-eligibility.yml
source_heading: Eligibility
source_page: https://www.tracktitan.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Track Titan\naid: track-titan\nurl: https://www.tracktitan.io/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use this Website.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use this Website.\n"
source_yaml_url: https://artifacts.apis.io/track-titan/eligibility/track-titan-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Track Titan's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Sim Racing
- Telemetry
- Gaming
- Motorsports
- Coaching
- Analytics
---
