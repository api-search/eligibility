---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Users may be located at any location around the world
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Platform limited to teaching business
    text: Use the Services or the Noon Platform for business other than providing tutoring, teaching, and instructional services to Users;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Courses will be made available to Users on or through the Noon Platform, once reviewed and approved by the Company
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Noon Academy
provenance_date: '2026-11-10'
provider_name: Noon Academy
provider_slug: noon-academy
slug: noon-academy-eligibility
source_date: '2026-11-10'
source_filename: noon-academy-eligibility.yml
source_heading: Eligibility
source_page: https://www.noonacademy.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Noon Academy\naid: noon-academy\nurl: https://www.noonacademy.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Users may be located at any location around the world\nentity_types: []\nrestricted_uses:\n- summary: Platform limited to teaching business\n  text: Use the Services or the Noon Platform for business other than providing tutoring, teaching, and instructional\n    services to Users;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Courses will be made available to Users on or through the Noon Platform, once reviewed and approved by the\n\
  \    Company\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/noon-academy/eligibility/noon-academy-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Noon Academy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- EdTech
- Social Learning
- E-Learning
- Tutoring
---
