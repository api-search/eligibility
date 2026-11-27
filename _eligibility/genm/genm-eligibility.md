---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a full-service marketing platform to business owners (“Customers”)
    type: business
  - text: students (“Students)
    type: individual
  minimum_age:
    text: You may use the Services only if you have reached the age of maturity in your jurisdiction of residence
    value: age of maturity in jurisdiction of residence
  restricted_uses:
  - summary: Unpaid work outside the platform
    text: Attempt to take students off from the platform to perform unpaid work not supervised by the Services.
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
name: GenM
provenance_date: '2026-11-09'
provider_name: GenM
provider_slug: genm
slug: genm-eligibility
source_date: '2026-11-09'
source_filename: genm-eligibility.yml
source_heading: Eligibility
source_page: https://www.acadium.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: GenM\naid: genm\nurl: https://www.acadium.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: a full-service marketing platform to business owners (“Customers”)\n- type: individual\n  text: students (“Students)\nrestricted_uses:\n- summary: Unpaid work outside the platform\n  text: Attempt to take students off from the platform to perform unpaid work not supervised by the Services.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of maturity in jurisdiction of residence\n\
  \  text: You may use the Services only if you have reached the age of maturity in your jurisdiction of residence\n"
source_yaml_url: https://artifacts.apis.io/genm/eligibility/genm-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from GenM's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Digital Marketing
- Education
- Apprenticeships
- Marketing Talent
- Online Courses
- Career Platform
- Mentorship
---
