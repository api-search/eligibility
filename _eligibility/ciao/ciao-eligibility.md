---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use MeetCiao.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use MeetCiao.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: all membership applications, including trials, are subject to approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ciao
provenance_date: '2026-11-09'
provider_name: Ciao
provider_slug: ciao
slug: ciao-eligibility
source_date: '2026-11-09'
source_filename: ciao-eligibility.yml
source_heading: Eligibility
source_page: https://meetciao.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ciao\naid: ciao\nurl: https://meetciao.com/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use MeetCiao.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: all membership applications, including trials, are subject to approval.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use MeetCiao.\n"
source_yaml_url: https://artifacts.apis.io/ciao/eligibility/ciao-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from Ciao's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Travel
- Home Sharing
- Hospitality
- Community
- Marketplace
- Consumer
- Seedcamp
---
