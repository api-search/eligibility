---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for your personal, non-commercial use.
    type: individual
  minimum_age:
    text: You represent that you are at least 18 years of age and have the legal capacity to enter into a binding contract in the jurisdiction where you reside.
    value: '18'
  restricted_uses:
  - summary: No commercial use
    text: You agree that you will not use any portion of the Software, the Site or the Service for any commercial purpose or the benefit of any third party
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
name: Kiwibot
provenance_date: '2026-11-09'
provider_name: Kiwibot
provider_slug: kiwibot
slug: kiwibot-eligibility
source_date: '2026-11-09'
source_filename: kiwibot-eligibility.yml
source_heading: Eligibility
source_page: https://www.robot.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kiwibot\naid: kiwibot\nurl: https://www.robot.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: solely for your personal, non-commercial use.\nrestricted_uses:\n- summary: No commercial use\n  text: You agree that you will not use any portion of the Software, the Site or the Service for any commercial\n    purpose or the benefit of any third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years of age\
  \ and have the legal capacity to enter into a binding\n    contract in the jurisdiction where you reside.\n"
source_yaml_url: https://artifacts.apis.io/kiwibot/eligibility/kiwibot-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Kiwibot's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Robotics
- Autonomous Vehicles
- Delivery
- Last Mile Delivery
- Logistics
- Warehouse Automation
- Advertising
- ROS
- Open Source
---
