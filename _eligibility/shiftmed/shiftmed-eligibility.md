---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: ShiftMed will not knowingly collect any information from individuals under 18.
    value: '18'
  restricted_uses:
  - summary: Full Site Services limited to employees
    text: Full access to these Site Services is restricted to employees of ShiftMed.
  - summary: No unlawful use
    text: Use the Site or Site Services for any unlawful purpose, or for the promotion of illegal activities;
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
name: ShiftMed
provenance_date: '2026-11-10'
provider_name: ShiftMed
provider_slug: shiftmed
slug: shiftmed-eligibility
source_date: '2026-11-10'
source_filename: shiftmed-eligibility.yml
source_heading: Eligibility
source_page: https://www.shiftmed.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ShiftMed\naid: shiftmed\nurl: https://www.shiftmed.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Full Site Services limited to employees\n  text: Full access to these Site Services is restricted to employees of ShiftMed.\n- summary: No unlawful use\n  text: Use the Site or Site Services for any unlawful purpose, or for the promotion of illegal activities;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: ShiftMed will not knowingly collect any information\
  \ from individuals under 18.\n"
source_yaml_url: https://artifacts.apis.io/shiftmed/eligibility/shiftmed-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from ShiftMed's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Staffing
- Workforce Management
- Scheduling
- Marketplace
- Nursing
- Human Resources
- Health Systems
---
