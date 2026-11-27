---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Client is a professional, understood as any natural or legal person acting for purposes falling within the scope of their commercial, industrial, artisanal, liberal, or agricultural activity
    type: business
  minimum_age:
    text: null
    value: null
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
name: Skello
provenance_date: '2026-11-10'
provider_name: Skello
provider_slug: skello
slug: skello-eligibility
source_date: '2026-11-10'
source_filename: skello-eligibility.yml
source_heading: Eligibility
source_page: https://www.skello.io/en/landing/general-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Skello\naid: skello\nurl: https://www.skello.io/en/landing/general-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Client is a professional, understood as any natural or legal person acting for purposes falling within\n    the scope of their commercial, industrial, artisanal, liberal, or agricultural activity\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/skello/eligibility/skello-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Skello's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Applicative Saas
- Workforce Management
- Employee Scheduling
- Time and Attendance
- Human Resources
- Shift Planning
- Payroll
- Scheduling
---
