---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account is for one person; you may not share, sell or transfer it.
    type: individual
  minimum_age:
    text: You must be at least 16 years old.
    value: '16'
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
name: Atlas Red
provenance_date: '2026-11-09'
provider_name: Atlas Red
provider_slug: atlas-red-com
slug: atlas-red-com-eligibility
source_date: '2026-11-09'
source_filename: atlas-red-com-eligibility.yml
source_heading: Eligibility
source_page: https://app.atlas-red.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Atlas Red\naid: atlas-red-com\nurl: https://app.atlas-red.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account is for one person; you may not share, sell or transfer it.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old.\n"
source_yaml_url: https://artifacts.apis.io/atlas-red-com/eligibility/atlas-red-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Atlas Red's own page on 2026-11-09.
synthetic: false
tags:
- Mind Mapping
- Productivity
- Software-as-a-Service
- no-subscription
- Export
---
