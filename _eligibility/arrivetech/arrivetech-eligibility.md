---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf of which such individual is accessing or using the Service
    type: individual
  minimum_age:
    text: You represent that you are over the age of 18. The Company does not permit those under 18 to use the Service.
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
name: Arrive AI
provenance_date: '2026-11-09'
provider_name: Arrive AI
provider_slug: arrivetech
slug: arrivetech-eligibility
source_date: '2026-11-09'
source_filename: arrivetech-eligibility.yml
source_heading: Eligibility
source_page: https://www.termsfeed.com/live/a14c73d9-ad66-4fd9-aa7f-a4b0f0f3b0dc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Arrive AI\naid: arrivetech\nurl: https://www.termsfeed.com/live/a14c73d9-ad66-4fd9-aa7f-a4b0f0f3b0dc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You means the individual accessing or using the Service, or the company, or other legal entity on behalf\n    of which such individual is accessing or using the Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are over the age of 18. The Company does not permit those\
  \ under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/arrivetech/eligibility/arrivetech-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Arrive AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Logistics
- Last Mile Delivery
- Autonomous Delivery
- Drones
- Robotics
- Smart Lockers
- Healthcare Logistics
- Supply Chain
- IoT
---
