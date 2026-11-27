---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You represent that you are at least the age of majority in the jurisdiction where you live or, if you are not, your parent or legal guardian must consent to this Terms of Service
    type: individual
  minimum_age:
    text: Use of the OnMyGrad Platform / AInterviewCoach.io by anyone under 15 years of age is prohibited.
    value: '15'
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
name: OnMyGrad
provenance_date: '2026-11-10'
provider_name: OnMyGrad
provider_slug: onmygrad
slug: onmygrad-eligibility
source_date: '2026-11-10'
source_filename: onmygrad-eligibility.yml
source_heading: Eligibility
source_page: https://onmygrad.space/tnc
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: OnMyGrad\naid: onmygrad\nurl: https://onmygrad.space/tnc\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You represent that you are at least the age of majority in the jurisdiction where you live or, if you are\n    not, your parent or legal guardian must consent to this Terms of Service\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '15'\n  text: Use of the OnMyGrad Platform / AInterviewCoach.io by anyone under 15 years of age is prohibited.\n"
source_yaml_url: https://artifacts.apis.io/onmygrad/eligibility/onmygrad-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from OnMyGrad's own page on 2026-11-10.
synthetic: false
tags:
- Company
- EdTech
- Recruiting
- Careers
- Human Resources
- Campus Recruitment
- Talent
- Software-as-a-Service
- Southeast Asia
---
