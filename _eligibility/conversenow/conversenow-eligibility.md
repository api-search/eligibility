---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you must be at least 18 (or the age of majority in your jurisdiction) to use the Services
    value: '18'
  restricted_uses:
  - summary: Barred persons
    text: You may not use the Services if you are barred under applicable law.
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
name: ConverseNow
provenance_date: '2026-11-09'
provider_name: ConverseNow
provider_slug: conversenow
slug: conversenow-eligibility
source_date: '2026-11-09'
source_filename: conversenow-eligibility.yml
source_heading: Eligibility
source_page: https://conversenow.ai/terms-and-conditions.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ConverseNow\naid: conversenow\nurl: https://conversenow.ai/terms-and-conditions.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Barred persons\n  text: You may not use the Services if you are barred under applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 (or the age of majority in your jurisdiction) to use the Services\n"
source_yaml_url: https://artifacts.apis.io/conversenow/eligibility/conversenow-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from ConverseNow's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Voice AI
- Conversational AI
- Restaurant
- Point-of-Sale
- Ordering
- Drive-Thru
- Speech Recognition
- Artificial Intelligence
- Food Service
---
