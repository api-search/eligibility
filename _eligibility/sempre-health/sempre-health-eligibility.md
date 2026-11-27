---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are 18 years or older and are not barred from using the Services under applicable law.
    type: individual
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: Discounts not valid for government-funded programs
    text: They are not valid for prescriptions that are eligible to be reimbursed in whole or in part under any state or federal government-funded healthcare program, such as Medicare, Medicaid, TRICARE, the Department of Defense, or Veterans Affairs.
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
name: Sempre Health
provenance_date: '2026-11-10'
provider_name: Sempre Health
provider_slug: sempre-health
slug: sempre-health-eligibility
source_date: '2026-11-10'
source_filename: sempre-health-eligibility.yml
source_heading: Eligibility
source_page: https://www.semprehealth.com/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sempre Health\naid: sempre-health\nurl: https://www.semprehealth.com/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and are not barred from using the Services under\n    applicable law.\nrestricted_uses:\n- summary: Discounts not valid for government-funded programs\n  text: They are not valid for prescriptions that are eligible to be reimbursed in whole or in part under any state\n    or federal government-funded healthcare program, such as Medicare, Medicaid, TRICARE,\
  \ the Department of Defense,\n    or Veterans Affairs.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/sempre-health/eligibility/sempre-health-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Sempre Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health
- Healthcare
- Digital Health
- Pharmacy
- Pharmacy Benefits
- Prescriptions
- Medication Adherence
- Patient Engagement
- Health Plans
- SMS
---
