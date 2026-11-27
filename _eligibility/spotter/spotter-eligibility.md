---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to use the Site or the Services.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use the Site or the Services.
    value: '16'
  restricted_uses:
  - summary: Users must not violate laws or infringe rights
    text: violate any law or regulation; violate or infringe upon any intellectual property, proprietary, privacy, moral, publicity or other rights of ours or of any other third party
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
name: Spotter
provenance_date: '2026-11-10'
provider_name: Spotter
provider_slug: spotter
slug: spotter-eligibility
source_date: '2026-11-10'
source_filename: spotter-eligibility.yml
source_heading: Eligibility
source_page: https://www.spotter.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spotter\naid: spotter\nurl: https://www.spotter.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use the Site or the Services.\nrestricted_uses:\n- summary: Users must not violate laws or infringe rights\n  text: violate any law or regulation; violate or infringe upon any intellectual property, proprietary, privacy,\n    moral, publicity or other rights of ours or of any other third party\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '16'\n  text: You must be at least 16 years old to use the Site or the Services.\n"
source_yaml_url: https://artifacts.apis.io/spotter/eligibility/spotter-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Spotter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Creator Economy
- Media
- YouTube
- Video
- Marketing
- Content
- Creators
- Artificial Intelligence
---
