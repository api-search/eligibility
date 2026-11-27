---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: this service is intended only for individuals who are at least 18 years of age or older.
    type: individual
  minimum_age:
    text: You must be 18 years or older to use this Service.
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorised use
    text: You may not use the Service for any illegal or unauthorised purpose.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide your legal full name, a valid email address, and any other information requested in order to complete the signup process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Memory
provenance_date: '2026-11-10'
provider_name: Memory
provider_slug: memory
slug: memory-eligibility
source_date: '2026-11-10'
source_filename: memory-eligibility.yml
source_heading: Eligibility
source_page: https://www.timely.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Memory\naid: memory\nurl: https://www.timely.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: this service is intended only for individuals who are at least 18 years of age or older.\nrestricted_uses:\n- summary: Illegal or unauthorised use\n  text: You may not use the Service for any illegal or unauthorised purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must provide your legal full name, a valid email address, and any other information requested in order\n    to complete the signup\
  \ process.\nminimum_age:\n  value: '18'\n  text: You must be 18 years or older to use this Service.\n"
source_yaml_url: https://artifacts.apis.io/memory/eligibility/memory-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Memory's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Time Tracking
- Timesheets
- Productivity
- Project Management
- Professional Services
- Reporting
- Automation
- Artificial Intelligence
- Software-as-a-Service
---
