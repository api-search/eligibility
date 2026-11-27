---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Rent a single bike from one of our workshops
    type: individual
  - text: choose “Business” if you are interested in a fleet
    type: business
  minimum_age:
    text: null
    value: null
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
name: Cycle
provenance_date: '2026-11-09'
provider_name: Cycle
provider_slug: cycle
slug: cycle-eligibility
source_date: '2026-11-09'
source_filename: cycle-eligibility.yml
source_heading: Eligibility
source_page: https://www.cycle.eco/t-c
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cycle\naid: cycle\nurl: https://www.cycle.eco/t-c\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Rent a single bike from one of our workshops\n- type: business\n  text: choose “Business” if you are interested in a fleet\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cycle/eligibility/cycle-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Cycle's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Micromobility
- E-Bikes
- Urban Mobility
- Delivery
- Logistics
- Transportation
- Subscription
- Sustainability
- Fleet Management
---
