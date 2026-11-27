---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old and meet any higher minimum age required by the laws where you live.
    type: individual
  minimum_age:
    text: You must be at least 13 years old and meet any higher minimum age required by the laws where you live.
    value: '13'
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
name: BriefMe
provenance_date: '2026-11-09'
provider_name: BriefMe
provider_slug: briefme-us
slug: briefme-us-eligibility
source_date: '2026-11-09'
source_filename: briefme-us-eligibility.yml
source_heading: Eligibility
source_page: https://briefme.us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BriefMe\naid: briefme-us\nurl: https://briefme.us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old and meet any higher minimum age required by the laws where you live.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old and meet any higher minimum age required by the laws where you live.\n"
source_yaml_url: https://artifacts.apis.io/briefme-us/eligibility/briefme-us-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from BriefMe's own page on 2026-11-09.
synthetic: false
tags:
- Timer
- Meetings
- Productivity
- Software-as-a-Service
- Free
---
