---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Be at least 18 years of age
    type: individual
  - text: Be authorized by your employer or company to access and use the Services on their behalf
    type: business
  minimum_age:
    text: Be at least 18 years of age
    value: '18'
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
name: Replenysh
provenance_date: '2026-11-10'
provider_name: Replenysh
provider_slug: replenysh
slug: replenysh-eligibility
source_date: '2026-11-10'
source_filename: replenysh-eligibility.yml
source_heading: Eligibility
source_page: https://replenysh.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Replenysh\naid: replenysh\nurl: https://replenysh.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Be at least 18 years of age\n- type: business\n  text: Be authorized by your employer or company to access and use the Services on their behalf\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/replenysh/eligibility/replenysh-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Replenysh's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Circular Economy
- Reverse Logistics
- Recycling
- Supply Chain
- Sustainability
- Materials
---
