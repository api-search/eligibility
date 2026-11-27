---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old, or the age of majority where you live, and legally able to enter into a binding contract to use the Service or place an order.
    type: individual
  - text: Non-consumer disputes will be administered under the AAA Commercial Arbitration Rules.
    type: business
  minimum_age:
    text: You must be at least 18 years old, or the age of majority where you live
    value: '18'
  restricted_uses:
  - summary: Restricted or safety-sensitive items
    text: Constitutes or facilitates a weapon, regulated firearm component, prohibited medical device, or another restricted or safety-sensitive item we choose not to manufacture
  - summary: Printed parts not for safety-critical use
    text: printed parts are not designed, tested, or certified for safety-critical, medical, life-support, protective, automotive, aerospace, load-bearing, or other high-risk or regulated uses
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
name: Aiurion
provenance_date: '2026-11-09'
provider_name: Aiurion
provider_slug: aiurion-com
slug: aiurion-com-eligibility
source_date: '2026-11-09'
source_filename: aiurion-com-eligibility.yml
source_heading: Eligibility
source_page: https://aiurion.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aiurion\naid: aiurion-com\nurl: https://aiurion.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority where you live, and legally able to enter into\n    a binding contract to use the Service or place an order.\n- type: business\n  text: Non-consumer disputes will be administered under the AAA Commercial Arbitration Rules.\nrestricted_uses:\n- summary: Restricted or safety-sensitive items\n  text: Constitutes or facilitates a weapon, regulated firearm component, prohibited\
  \ medical device, or another\n    restricted or safety-sensitive item we choose not to manufacture\n- summary: Printed parts not for safety-critical use\n  text: printed parts are not designed, tested, or certified for safety-critical, medical, life-support, protective,\n    automotive, aerospace, load-bearing, or other high-risk or regulated uses\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority where you live\n"
source_yaml_url: https://artifacts.apis.io/aiurion-com/eligibility/aiurion-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Aiurion's own page on 2026-11-09.
synthetic: false
tags:
- 3D Printing
- Manufacturing
- Rapid Prototyping
- San Francisco
- Hardware
---
