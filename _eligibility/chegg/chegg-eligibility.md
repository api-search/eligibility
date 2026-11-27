---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Services are available to individuals age 13 and over.
    type: individual
  minimum_age:
    text: The Services are available to individuals age 13 and over.
    value: '13'
  restricted_uses:
  - summary: AI features limited to adults
    text: AI features are available only to users who are 18 or older.
  - summary: Career features limited to adults
    text: These career features are available only to users who are 18 or older.
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
name: Chegg
provenance_date: '2026-11-09'
provider_name: Chegg
provider_slug: chegg
slug: chegg-eligibility
source_date: '2026-11-09'
source_filename: chegg-eligibility.yml
source_heading: Eligibility
source_page: https://www.chegg.com/en-US/termsofuse
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chegg\naid: chegg\nurl: https://www.chegg.com/en-US/termsofuse\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Services are available to individuals age 13 and over.\nrestricted_uses:\n- summary: AI features limited to adults\n  text: AI features are available only to users who are 18 or older.\n- summary: Career features limited to adults\n  text: These career features are available only to users who are 18 or older.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: The Services are available to individuals age 13 and over.\n"
source_yaml_url: https://artifacts.apis.io/chegg/eligibility/chegg-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Chegg's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Education
- EdTech
- Learning
- Students
- Homework Help
- Textbooks
---
