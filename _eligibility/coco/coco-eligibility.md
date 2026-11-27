---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: These Retailer Program Terms and Conditions (these “Terms”) set forth the legal terms entered into between the Retailer identified on the Pricing Addendum
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No tobacco product advertising or sales on Marketplace
    text: Retailers may not advertise or sell tobacco products on the Coco Marketplace.
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
name: Coco Robotics
provenance_date: '2026-11-09'
provider_name: Coco Robotics
provider_slug: coco
slug: coco-eligibility
source_date: '2026-11-09'
source_filename: coco-eligibility.yml
source_heading: Eligibility
source_page: https://www.cocodelivery.com/merchant-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Coco Robotics\naid: coco\nurl: https://www.cocodelivery.com/merchant-terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: These Retailer Program Terms and Conditions (these “Terms”) set forth the legal terms entered into between\n    the Retailer identified on the Pricing Addendum\nrestricted_uses:\n- summary: No tobacco product advertising or sales on Marketplace\n  text: Retailers may not advertise or sell tobacco products on the Coco Marketplace.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/coco/eligibility/coco-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Coco Robotics's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Robotics
- Delivery
- Logistics
- Last Mile Delivery
- Autonomous Vehicles
- Urban Mobility
- Food Delivery
- Advertising
- Fleet Management
---
