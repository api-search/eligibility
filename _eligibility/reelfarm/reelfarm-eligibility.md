---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use ReelFarm. If you are under 18, you need a parent or guardian's permission.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use ReelFarm.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: 'To use ReelFarm, you must: Have a valid Google account Provide accurate account information'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ReelFarm
provenance_date: '2026-11-10'
provider_name: ReelFarm
provider_slug: reelfarm
slug: reelfarm-eligibility
source_date: '2026-11-10'
source_filename: reelfarm-eligibility.yml
source_heading: Eligibility
source_page: https://reel.farm/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ReelFarm\naid: reelfarm\nurl: https://reel.farm/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use ReelFarm. If you are under 18, you need a parent or guardian's\n    permission.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: 'To use ReelFarm, you must: Have a valid Google account Provide accurate account information'\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use ReelFarm.\n"
source_yaml_url: https://artifacts.apis.io/reelfarm/eligibility/reelfarm-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from ReelFarm's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- TikTok
- Automation
- Video Marketing
---
