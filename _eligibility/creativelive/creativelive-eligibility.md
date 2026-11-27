---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: You are granted a limited, revocable, non-transferable license to use the Service for personal, non-commercial purposes only.
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
name: creativeLIVE
provenance_date: '2026-11-09'
provider_name: creativeLIVE
provider_slug: creativelive
slug: creativelive-eligibility
source_date: '2026-11-09'
source_filename: creativelive-eligibility.yml
source_heading: Eligibility
source_page: https://www.creativelive.com/policies
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: creativeLIVE\naid: creativelive\nurl: https://www.creativelive.com/policies\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: You are granted a limited, revocable, non-transferable license to use the Service for personal, non-commercial\n    purposes only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to\
  \ use the Service.\n"
source_yaml_url: https://artifacts.apis.io/creativelive/eligibility/creativelive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from creativeLIVE's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Education
- E-Learning
- Courses
- Photography
- Video
- Design
- Creative
---
