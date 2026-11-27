---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service. If you are located in the UK/EEA, you must be at least 16 years old unless you have parental consent.
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
name: StoryCut
provenance_date: '2026-11-10'
provider_name: StoryCut
provider_slug: storycut-com
slug: storycut-com-eligibility
source_date: '2026-11-10'
source_filename: storycut-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.storycut.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StoryCut\naid: storycut-com\nurl: https://www.storycut.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use the Service.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service. If you are located in the UK/EEA, you must be at least\n    16 years old unless you have parental consent.\n"
source_yaml_url: https://artifacts.apis.io/storycut-com/eligibility/storycut-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from StoryCut's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Video
- Social Media
- Automation
---
