---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Not for life-saving or emergency systems
    text: The Products and Services are not intended to be used as part of any life-saving or emergency systems
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
name: Butlr
provenance_date: '2026-11-09'
provider_name: Butlr
provider_slug: butlr
slug: butlr-eligibility
source_date: '2026-11-09'
source_filename: butlr-eligibility.yml
source_heading: Eligibility
source_page: https://www.butlr.com/legal/tc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Butlr\naid: butlr\nurl: https://www.butlr.com/legal/tc\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Not for life-saving or emergency systems\n  text: The Products and Services are not intended to be used as part of any life-saving or emergency systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/butlr/eligibility/butlr-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Butlr's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sensors
- Occupancy
- People Sensing
- Smart Buildings
- Spatial Intelligence
- IoT
- GraphQL
- Webhook
- Real Estate
---
