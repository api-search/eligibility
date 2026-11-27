---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Bloomberg operates this site in the United States. Bloomberg makes no representation that materials in this site are appropriate or available for use in other locations.
  entity_types:
  - text: you are at least eighteen (18) years old
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: You may not use the Service for any illegal purpose
  - summary: Noncommercial use only
    text: You agree to use the Service solely for your own noncommercial use and benefit
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: BLP reserves the right to deny creation of your account based on BLP’s inability to verify the authenticity of your registration information.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Bloomberg Government (BGOV)
provenance_date: '2026-11-09'
provider_name: Bloomberg Government (BGOV)
provider_slug: bloomberg-government-bgov
slug: bloomberg-government-bgov-eligibility
source_date: '2026-11-09'
source_filename: bloomberg-government-bgov-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomberg Government (BGOV)\naid: bloomberg-government-bgov\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Bloomberg operates this site in the United States. Bloomberg makes no representation that materials in this\n    site are appropriate or available for use in other locations.\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years old\nrestricted_uses:\n- summary: Illegal purposes\n  text: You may not use the Service for any illegal purpose\n- summary: Noncommercial use only\n  text:\
  \ You agree to use the Service solely for your own noncommercial use and benefit\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: BLP reserves the right to deny creation of your account based on BLP’s inability to verify the authenticity\n    of your registration information.\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-government-bgov/eligibility/bloomberg-government-bgov-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Bloomberg Government (BGOV)'s own page on 2026-11-09.
synthetic: false
tags:
- Government
- Legislative
- Regulatory
- Government Contracting
- Federal Budget
- Policy Research
- Bloomberg
---
