---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Linked bank accounts must be U.S. bank accounts; fees quoted in United States dollars. No explicit country served/excluded list stated.
  entity_types:
  - text: IF YOU ENTER INTO AN ORDER FORM ON BEHALF OF A COMPANY, ORGANIZATION OR ENTITY, YOU REPRESENT THAT (A) YOU ARE AN AUTHORIZED REPRESENTATIVE OF SUCH ENTITY
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Covered entities under HIPAA
    text: If You are a covered entity under the Health Insurance Portability and Accountability Act, as amended by the Health Information Technology for Economic and Clinical Health Act, then You shall enter into the Business Associate Agreement
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
name: Jolly
provenance_date: '2026-11-09'
provider_name: Jolly
provider_slug: jolly
slug: jolly-eligibility
source_date: '2026-11-09'
source_filename: jolly-eligibility.yml
source_heading: Eligibility
source_page: https://jolly.com/employers/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Jolly\naid: jolly\nurl: https://jolly.com/employers/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Linked bank accounts must be U.S. bank accounts; fees quoted in United States dollars. No explicit country\n    served/excluded list stated.\nentity_types:\n- type: business\n  text: IF YOU ENTER INTO AN ORDER FORM ON BEHALF OF A COMPANY, ORGANIZATION OR ENTITY, YOU REPRESENT THAT (A) YOU\n    ARE AN AUTHORIZED REPRESENTATIVE OF SUCH ENTITY\nrestricted_uses:\n- summary: Covered entities under HIPAA\n  text: If You are a covered entity under the Health Insurance\
  \ Portability and Accountability Act, as amended by\n    the Health Information Technology for Economic and Clinical Health Act, then You shall enter into the Business\n    Associate Agreement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jolly/eligibility/jolly-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Jolly's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Workforce Engagement
- Employee Rewards
- Gamification
- Human Resources
- Frontline Workforce
- Workforce Management
- Recruiting
- Incentives
- Loyalty & Incentives
---
