---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a person searching for additional educational opportunities using the ApplyBoard Platform directly to research and apply
    type: individual
  - text: any School, company, organization, association or individual that has entered into an agreement with ApplyBoard
    type: business
  minimum_age:
    text: you represent that you have reached the age of majority in your jurisdiction
    value: age of majority
  restricted_uses:
  - summary: No dangerous or time-critical use
    text: The ApplyBoard Platform is not developed or licensed for use in any inherently dangerous, time-sensitive, or mission critical manner.
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
name: ApplyBoard
provenance_date: '2026-11-09'
provider_name: ApplyBoard
provider_slug: applyboard
slug: applyboard-eligibility
source_date: '2026-11-09'
source_filename: applyboard-eligibility.yml
source_heading: Eligibility
source_page: https://www.applyboard.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ApplyBoard\naid: applyboard\nurl: https://www.applyboard.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a person searching for additional educational opportunities using the ApplyBoard Platform directly to research\n    and apply\n- type: business\n  text: any School, company, organization, association or individual that has entered into an agreement with ApplyBoard\nrestricted_uses:\n- summary: No dangerous or time-critical use\n  text: The ApplyBoard Platform is not developed or licensed\
  \ for use in any inherently dangerous, time-sensitive,\n    or mission critical manner.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you have reached the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/applyboard/eligibility/applyboard-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from ApplyBoard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- International Education
- Study Abroad
- Student Recruitment
- Document Verification
---
