---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you (if you are an individual) are at least 18 years of age, can form legally-binding contracts
    type: individual
  - text: you (if you are the representative of an entity) are the representative of the entity that is entering into this Agreement and are authorized to act on its behalf
    type: business
  minimum_age:
    text: you (if you are an individual) are at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful content or conduct
    text: You may not post content on or communicate through the AllWork Platform in violation of any applicable law
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Client must be approved by AllWork before accessing certain functionality of the AllWork Platform, including but not limited to (1) Jobs being posted live, (2) searching Talent, and (3) messaging Talent.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AllWork
provenance_date: '2026-11-09'
provider_name: AllWork
provider_slug: allwork
slug: allwork-eligibility
source_date: '2026-11-09'
source_filename: allwork-eligibility.yml
source_heading: Eligibility
source_page: https://allworknow.com/terms-of-use-2/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AllWork\naid: allwork\nurl: https://allworknow.com/terms-of-use-2/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you (if you are an individual) are at least 18 years of age, can form legally-binding contracts\n- type: business\n  text: you (if you are the representative of an entity) are the representative of the entity that is entering into\n    this Agreement and are authorized to act on its behalf\nrestricted_uses:\n- summary: Unlawful content or conduct\n  text: You may not post content on or communicate through the AllWork Platform\
  \ in violation of any applicable law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Client must be approved by AllWork before accessing certain functionality of the AllWork Platform, including\n    but not limited to (1) Jobs being posted live, (2) searching Talent, and (3) messaging Talent.\nminimum_age:\n  value: '18'\n  text: you (if you are an individual) are at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/allwork/eligibility/allwork-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from AllWork's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Workforce Management
- Human Resources
- Staffing
- Payroll
- Employer of Record
- Contingent Workforce
- Gig Economy
- Scheduling
- Time and Attendance
- Compliance
---
