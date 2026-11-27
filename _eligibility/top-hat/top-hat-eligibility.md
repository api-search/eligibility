---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: 'Top Hat entity varies by user location: United States, Australia or New Zealand, and Canada or elsewhere outside those (per Section 1.16).'
  minimum_age:
    text: you are at least 18 years of age and you have the legal authority to enter into this Agreement and use the Products
    value: '18'
  restricted_uses:
  - summary: Academic dishonesty
    text: inquire about, engage in, or aid or assist anyone with any form of academic dishonesty or violations of academic integrity policies
  - summary: Hazardous uses
    text: use all or any portion of the Products for hazardous purposes requiring fail-safe performance, such as aircraft navigation, air traffic control, or weapons systems
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
name: Top Hat
provenance_date: '2026-11-10'
provider_name: Top Hat
provider_slug: top-hat
slug: top-hat-eligibility
source_date: '2026-11-10'
source_filename: top-hat-eligibility.yml
source_heading: Eligibility
source_page: https://tophat.com/company/legal/user-agreement/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Top Hat\naid: top-hat\nurl: https://tophat.com/company/legal/user-agreement/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: 'Top Hat entity varies by user location: United States, Australia or New Zealand, and Canada or elsewhere\n    outside those (per Section 1.16).'\nentity_types: []\nrestricted_uses:\n- summary: Academic dishonesty\n  text: inquire about, engage in, or aid or assist anyone with any form of academic dishonesty or violations of\n    academic integrity policies\n- summary: Hazardous uses\n  text: use all or any portion of the Products for hazardous purposes requiring\
  \ fail-safe performance, such as aircraft\n    navigation, air traffic control, or weapons systems\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age and you have the legal authority to enter into this Agreement and use the\n    Products\n"
source_yaml_url: https://artifacts.apis.io/top-hat/eligibility/top-hat-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Top Hat's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EdTech
- Education
- Higher Education
- LMS
- Student Engagement
- Interactive Learning
- Courseware
- Assessment
---
