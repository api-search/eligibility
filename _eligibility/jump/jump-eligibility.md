---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Software from the Platform may not be downloaded, exported, or re-exported into Cuba, Crimea, North Korea, Iran, Syria, or any other country to which the United States has embargoed goods
  minimum_age:
    text: Includes video, audio, or images of any person younger than 18
    value: null
  restricted_uses:
  - summary: Impersonation and automated access
    text: Impersonates any person or entity, including any employee or representative of Jump
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
name: Jump
provenance_date: '2026-11-09'
provider_name: Jump
provider_slug: jump
slug: jump-eligibility
source_date: '2026-11-09'
source_filename: jump-eligibility.yml
source_heading: Eligibility
source_page: https://www.jump.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jump\naid: jump\nurl: https://www.jump.com/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Software from the Platform may not be downloaded, exported, or re-exported into Cuba, Crimea, North Korea,\n    Iran, Syria, or any other country to which the United States has embargoed goods\nentity_types: []\nrestricted_uses:\n- summary: Impersonation and automated access\n  text: Impersonates any person or entity, including any employee or representative of Jump\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ Includes video, audio, or images of any person younger than 18\n"
source_yaml_url: https://artifacts.apis.io/jump/eligibility/jump-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Jump's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sports
- Ticketing
- Fan Experience
- Event
- Marketing
- Loyalty
- Artificial Intelligence
---
