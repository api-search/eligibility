---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are made available globally.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Calling Service prohibited uses
    text: make calls to any individual or entity that has opted out or requested to not be contacted
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
name: Spyne
provenance_date: '2026-11-10'
provider_name: Spyne
provider_slug: spyne
slug: spyne-eligibility
source_date: '2026-11-10'
source_filename: spyne-eligibility.yml
source_heading: Eligibility
source_page: https://www.spyne.ai/terms-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spyne\naid: spyne\nurl: https://www.spyne.ai/terms-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are made available globally.\nentity_types: []\nrestricted_uses:\n- summary: Calling Service prohibited uses\n  text: make calls to any individual or entity that has opted out or requested to not be contacted\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/spyne/eligibility/spyne-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from Spyne's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Automotive
- Image
- Video
- Computer Vision
- Machine Learning
- Dealership
- Media Processing
- Webhook
---
