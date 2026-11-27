---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Use void where prohibited
    text: Use of the Platform or Services is void where prohibited.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: The decision to accept a registration is within our sole discretion and We may revoke a registration at any time.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Remofirst
provenance_date: '2026-11-10'
provider_name: Remofirst
provider_slug: remofirst
slug: remofirst-eligibility
source_date: '2026-11-10'
source_filename: remofirst-eligibility.yml
source_heading: Eligibility
source_page: https://www.remofirst.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Remofirst\naid: remofirst\nurl: https://www.remofirst.com/legal/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use void where prohibited\n  text: Use of the Platform or Services is void where prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: The decision to accept a registration is within our sole discretion and We may revoke a registration at\n    any time.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/remofirst/eligibility/remofirst-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Remofirst's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Employer of Record
- Global Payroll
- Human Resources
- Contractors
- Compliance
---
