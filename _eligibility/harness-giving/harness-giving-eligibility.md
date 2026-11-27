---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: In order to be eligible as a Payment Card, it must be issued by a U.S. bank.
  entity_types:
  - text: You may only seek to open an Account for yourself and not on behalf of any other person.
    type: individual
  minimum_age:
    text: To use the Services, you must be 18 years of age (or the age of majority in the state in which you reside).
    value: '18'
  restricted_uses:
  - summary: Personal consumer use only
    text: solely for Your personal use in your capacity as an individual consumer and for no other purpose.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: We retain the right, in our sole and exclusive discretion, to approve your Account for registration, and we are under no obligation to grant such approval.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Harness (nonprofit giving app)
provenance_date: '2026-11-09'
provider_name: Harness (nonprofit giving app)
provider_slug: harness-giving
slug: harness-giving-eligibility
source_date: '2026-11-09'
source_filename: harness-giving-eligibility.yml
source_heading: Eligibility
source_page: https://goharness.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Harness (nonprofit giving app)\naid: harness-giving\nurl: https://goharness.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: In order to be eligible as a Payment Card, it must be issued by a U.S. bank.\nentity_types:\n- type: individual\n  text: You may only seek to open an Account for yourself and not on behalf of any other person.\nrestricted_uses:\n- summary: Personal consumer use only\n  text: solely for Your personal use in your capacity as an individual consumer and for no other purpose.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: We\
  \ retain the right, in our sole and exclusive discretion, to approve your Account for registration, and\n    we are under no obligation to grant such approval.\nminimum_age:\n  value: '18'\n  text: To use the Services, you must be 18 years of age (or the age of majority in the state in which you reside).\n"
source_yaml_url: https://artifacts.apis.io/harness-giving/eligibility/harness-giving-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Harness (nonprofit giving app)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Non-Profit
- Giving
- Recurring Payments
- Software-as-a-Service
---
