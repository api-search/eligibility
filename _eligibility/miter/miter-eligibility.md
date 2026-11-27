---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Platform for use only by persons located in the United States.
  minimum_age:
    text: This Platform is offered and available to users who are 18 years of age or older.
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You may use the Platform, including Payment Card Networks (Visa, Mastercard), only for lawful purposes and in accordance with these Employer Terms.
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
name: Miter
provenance_date: '2026-11-10'
provider_name: Miter
provider_slug: miter
slug: miter-eligibility
source_date: '2026-11-10'
source_filename: miter-eligibility.yml
source_heading: Eligibility
source_page: https://www.miter.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Miter\naid: miter\nurl: https://www.miter.com/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Platform for use only by persons located in the United States.\nentity_types: []\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You may use the Platform, including Payment Card Networks (Visa, Mastercard), only for lawful purposes and\n    in accordance with these Employer Terms.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Platform is offered and available to\
  \ users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/miter/eligibility/miter-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Miter's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Vertical Software
- Construction
- Payroll
- HCM
- Human Resources
- Field Operations
- Expense Management
- Workforce Management
- Fintech
---
