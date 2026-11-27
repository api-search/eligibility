---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are 16 years of age or older, you are fully able, competent, and authorized to enter into this binding Agreement
    type: individual
  minimum_age:
    text: you are 16 years of age or older
    value: '16'
  restricted_uses:
  - summary: Personal use only
    text: your access and use of the Site/Services are for your personal use
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
name: SuperQuickQuestion
provenance_date: '2026-11-10'
provider_name: SuperQuickQuestion
provider_slug: superquickquestion
slug: superquickquestion-eligibility
source_date: '2026-11-10'
source_filename: superquickquestion-eligibility.yml
source_heading: Eligibility
source_page: https://www.superquickquestion.com/terms_of_use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SuperQuickQuestion\naid: superquickquestion\nurl: https://www.superquickquestion.com/terms_of_use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are 16 years of age or older, you are fully able, competent, and authorized to enter into this binding\n    Agreement\nrestricted_uses:\n- summary: Personal use only\n  text: your access and use of the Site/Services are for your personal use\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: you are 16 years of age or\
  \ older\n"
source_yaml_url: https://artifacts.apis.io/superquickquestion/eligibility/superquickquestion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SuperQuickQuestion's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Video
- Fan Engagement
- Sports
- Entertainment
- Celebrity
- Marketing
- Video Calling
---
