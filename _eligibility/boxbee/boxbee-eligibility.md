---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: CUSTOMER or an authorized representative over 18 years of age must be at the pickup or delivery location in order to receive or send for delivery any Stored Goods.
    value: '18'
  restricted_uses:
  - summary: Prohibited storage materials
    text: CUSTOMER shall not, at any time, store with Boxbee, any narcotics, materials considered to be highly flammable, explosive, toxic, radioactive, organic material
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
name: Boxbee
provenance_date: '2026-11-09'
provider_name: Boxbee
provider_slug: boxbee
slug: boxbee-eligibility
source_date: '2026-11-09'
source_filename: boxbee-eligibility.yml
source_heading: Eligibility
source_page: https://boxbee.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Boxbee\naid: boxbee\nurl: https://boxbee.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited storage materials\n  text: CUSTOMER shall not, at any time, store with Boxbee, any narcotics, materials considered to be highly flammable,\n    explosive, toxic, radioactive, organic material\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: CUSTOMER or an authorized representative over 18 years of age must be at the pickup or delivery location\n\
  \    in order to receive or send for delivery any Stored Goods.\n"
source_yaml_url: https://artifacts.apis.io/boxbee/eligibility/boxbee-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Boxbee's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Storage
- On-Demand Storage
- Self Storage
- Moving
- Moving Boxes
- Logistics
---
