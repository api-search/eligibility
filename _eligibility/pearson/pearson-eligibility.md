---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: IF YOU ARE UNDER 18 YEARS OF AGE, PLEASE BE SURE TO READ THIS AGREEMENT WITH YOUR PARENTS OR GUARDIAN
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: for non-commercial, personal use only
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
name: Pearson
provenance_date: '2026-11-10'
provider_name: Pearson
provider_slug: pearson
slug: pearson-eligibility
source_date: '2026-11-10'
source_filename: pearson-eligibility.yml
source_heading: Eligibility
source_page: https://www.pearson.com/en-us/legal-information/terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pearson\naid: pearson\nurl: https://www.pearson.com/en-us/legal-information/terms-of-use.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: for non-commercial, personal use only\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: IF YOU ARE UNDER 18 YEARS OF AGE, PLEASE BE SURE TO READ THIS AGREEMENT WITH YOUR PARENTS OR GUARDIAN\n"
source_yaml_url: https://artifacts.apis.io/pearson/eligibility/pearson-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Pearson's own page on 2026-11-10.
synthetic: false
tags:
- Education
- Learning
- Assessment
- Certification
- Publishing
- EdTech
- Qualifications
- Testing
- LMS
- Workforce Skills
---
