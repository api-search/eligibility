---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years of age to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age to use our Services.
    value: '18'
  restricted_uses:
  - summary: Commercial use
    text: Sell, resell, or commercially use our Services;
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
name: Waymo
provenance_date: '2026-11-10'
provider_name: Waymo
provider_slug: waymo
slug: waymo-eligibility
source_date: '2026-11-10'
source_filename: waymo-eligibility.yml
source_heading: Eligibility
source_page: https://waymo.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Waymo\naid: waymo\nurl: https://waymo.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age to use our Services.\nrestricted_uses:\n- summary: Commercial use\n  text: Sell, resell, or commercially use our Services;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/waymo/eligibility/waymo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Waymo's own page on 2026-11-10.
synthetic: false
tags:
- Autonomous Vehicles
- Self-Driving
- Robotaxi
- Ride Hailing
- Alphabet
- LiDAR
- Computer Vision
- Open Dataset
- Simulation
- Mobility
---
