---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years old to register for or use the Platform.
    value: '18'
  restricted_uses:
  - summary: Prohibited disruptive or fake-account activity
    text: 'Examples of disruption that are prohibited include: (a) trying to edit or modify the Platform, as explained in 5.2; (b) using our Platform in any way that is unlawful'
  - summary: No sharing of account
    text: Your account is personal to you and must not be used by, or shared with, any other person.
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
name: Spill
provenance_date: '2026-11-10'
provider_name: Spill
provider_slug: spill
slug: spill-eligibility
source_date: '2026-11-10'
source_filename: spill-eligibility.yml
source_heading: Eligibility
source_page: https://www.spill.chat/legals/ts-and-cs
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Spill\naid: spill\nurl: https://www.spill.chat/legals/ts-and-cs\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Prohibited disruptive or fake-account activity\n  text: 'Examples of disruption that are prohibited include: (a) trying to edit or modify the Platform, as explained\n    in 5.2; (b) using our Platform in any way that is unlawful'\n- summary: No sharing of account\n  text: Your account is personal to you and must not be used by, or shared with, any other person.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to register for or use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/spill/eligibility/spill-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Spill's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mental Health
- Employee Assistance Program
- Wellbeing
- Human Resources
- Counselling
- Therapy
- Slack
- Software-as-a-Service
---
