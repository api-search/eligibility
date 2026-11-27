---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    - CA
    - GB
    - US
    - PL
    text: United Kingdom PayPal UK Ltd United States PayPal, Inc. (contracting entities by residence; Poland has its own agreement)
  entity_types:
  - text: Only natural persons are eligible to use the Xoom service.
    type: individual
  minimum_age:
    text: you must be (i) at least eighteen (18) years old or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Commercial purposes prohibited
    text: You agree that you will only use the Service to Send Money or purchase Reloads for personal reasons.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Recipients may be required to prove their identity before receiving funds by presenting authentic, valid, and current identification document(s)
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Xoom
provenance_date: '2026-11-10'
provider_name: Xoom
provider_slug: xoom
slug: xoom-eligibility
source_date: '2026-11-10'
source_filename: xoom-eligibility.yml
source_heading: Eligibility
source_page: https://www.xoom.com/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Xoom\naid: xoom\nurl: https://www.xoom.com/user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - AU\n  - CA\n  - GB\n  - US\n  - PL\n  excluded: []\n  text: United Kingdom PayPal UK Ltd United States PayPal, Inc. (contracting entities by residence; Poland has its\n    own agreement)\nentity_types:\n- type: individual\n  text: Only natural persons are eligible to use the Xoom service.\nrestricted_uses:\n- summary: Commercial purposes prohibited\n  text: You agree that you will only use the Service to Send Money or purchase Reloads for personal reasons.\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: Recipients may be required to prove their identity before receiving funds by presenting authentic, valid,\n    and current identification document(s)\nminimum_age:\n  value: '18'\n  text: you must be (i) at least eighteen (18) years old or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/xoom/eligibility/xoom-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Xoom's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Money Transfer
- Remittances
- Cross-Border Payments
- Payments
- PayPal
---
