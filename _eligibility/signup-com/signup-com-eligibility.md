---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site and its contents may only be accessed for personal use.
    type: individual
  minimum_age:
    text: You are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Prohibited activities list
    text: 'You may not use the SignUp.com service for activities that: violate any law, statute, ordinance or regulation'
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
name: SignUp.com
provenance_date: '2026-11-10'
provider_name: SignUp.com
provider_slug: signup-com
slug: signup-com-eligibility
source_date: '2026-11-10'
source_filename: signup-com-eligibility.yml
source_heading: Eligibility
source_page: https://signup.com/Terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SignUp.com\naid: signup-com\nurl: https://signup.com/Terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site and its contents may only be accessed for personal use.\nrestricted_uses:\n- summary: Prohibited activities list\n  text: 'You may not use the SignUp.com service for activities that: violate any law, statute, ordinance or regulation'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/signup-com/eligibility/signup-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from SignUp.com's own page on 2026-11-10.
synthetic: false
tags:
- Software-as-a-Service
- Scheduling
- Volunteer
- Education
- Non-Profit
---
