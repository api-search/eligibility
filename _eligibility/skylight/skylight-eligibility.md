---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Provider grants you the right to access and use the Platforms during the Term for your internal business operations only.
    type: business
  - text: You must be at least 16 years old to use the Platforms.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use the Platforms.
    value: '16'
  restricted_uses:
  - summary: Prohibited data categories
    text: 'You acknowledge that the Platforms are not designed for Processing the following categories of information:'
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
name: Skylight
provenance_date: '2026-11-10'
provider_name: Skylight
provider_slug: skylight
slug: skylight-eligibility
source_date: '2026-11-10'
source_filename: skylight-eligibility.yml
source_heading: Eligibility
source_page: https://www.skylight.io/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skylight\naid: skylight\nurl: https://www.skylight.io/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Provider grants you the right to access and use the Platforms during the Term for your internal business\n    operations only.\n- type: individual\n  text: You must be at least 16 years old to use the Platforms.\nrestricted_uses:\n- summary: Prohibited data categories\n  text: 'You acknowledge that the Platforms are not designed for Processing the following categories of information:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Platforms.\n"
source_yaml_url: https://artifacts.apis.io/skylight/eligibility/skylight-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Skylight's own page on 2026-11-10.
synthetic: false
tags:
- Performance
- Ruby
- Ruby on Rails
- Monitoring
- Profiling
- Company
---
