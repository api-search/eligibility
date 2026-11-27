---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Company controls and operates the Site and the Services from the United States and does not claim that any part of the Site is appropriate or may be accessed or used outside of the United States.
  entity_types:
  - text: You represent that you are at least 18 years of age (or the age of majority in the State in which you reside).
    type: individual
  minimum_age:
    text: You represent that you are at least 18 years of age (or the age of majority in the State in which you reside).
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: use the Site or the Services in a manner that is inconsistent with any and all applicable laws and regulations.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Company may require verification of information prior to the acceptance and/or fulfillment of any order.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Stepful
provenance_date: '2026-11-10'
provider_name: Stepful
provider_slug: stepful
slug: stepful-eligibility
source_date: '2026-11-10'
source_filename: stepful-eligibility.yml
source_heading: Eligibility
source_page: https://www.stepful.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Stepful\naid: stepful\nurl: https://www.stepful.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Company controls and operates the Site and the Services from the United States and does not claim that any\n    part of the Site is appropriate or may be accessed or used outside of the United States.\nentity_types:\n- type: individual\n  text: You represent that you are at least 18 years of age (or the age of majority in the State in which you reside).\nrestricted_uses:\n- summary: Unlawful use\n  text: use the Site or the Services in a manner that is inconsistent\
  \ with any and all applicable laws and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Company may require verification of information prior to the acceptance and/or fulfillment of any order.\nminimum_age:\n  value: '18'\n  text: You represent that you are at least 18 years of age (or the age of majority in the State in which you reside).\n"
source_yaml_url: https://artifacts.apis.io/stepful/eligibility/stepful-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Stepful's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Education
- Healthcare
- Workforce Development
- E-Learning
- Certification
- Allied Health
- Career Training
- Staffing
- EdTech
---
