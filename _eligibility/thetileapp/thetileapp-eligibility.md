---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all Service features may be available in your country.
  entity_types:
  - text: The Products and Services are intended for use by individuals and not by entities or businesses (for example, church groups, schools, corporations or businesses).
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited uses list
    text: violating, or promoting the violation of, this Agreement or any applicable law or regulation
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Tile (thetileapp)
provenance_date: '2026-11-10'
provider_name: Tile (thetileapp)
provider_slug: thetileapp
slug: thetileapp-eligibility
source_date: '2026-11-10'
source_filename: thetileapp-eligibility.yml
source_heading: Eligibility
source_page: https://legal.corp.life360.com/hc/en-us/articles/16124856472471-Life360-Terms-of-Service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tile (thetileapp)\naid: thetileapp\nurl: https://legal.corp.life360.com/hc/en-us/articles/16124856472471-Life360-Terms-of-Service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Not all Service features may be available in your country.\nentity_types:\n- type: individual\n  text: The Products and Services are intended for use by individuals and not by entities or businesses (for example,\n    church groups, schools, corporations or businesses).\nrestricted_uses:\n- summary: Prohibited uses list\n  text: violating, or promoting the violation of, this Agreement or\
  \ any applicable law or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/thetileapp/eligibility/thetileapp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Tile (thetileapp)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Bluetooth
- Location
- Tracking
- Consumer Electronics
- IoT
- Find My
- Life360
---
