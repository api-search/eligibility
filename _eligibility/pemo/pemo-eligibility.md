---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only businesses and individuals conducting a legitimate business activity are eligible to apply for a Pemo account
    type: business
  - text: Only businesses and individuals conducting a legitimate business activity are eligible to apply for a Pemo account
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Corporate expenses only
    text: you will only use the Pemo Account and Services for corporate expenses excluding salary payments.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Until you have submitted, and we have reviewed and approved all required information, your Pemo Account will be available to you on a limited basis only
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Pemo
provenance_date: '2026-11-10'
provider_name: Pemo
provider_slug: pemo
slug: pemo-eligibility
source_date: '2026-11-10'
source_filename: pemo-eligibility.yml
source_heading: Eligibility
source_page: https://www.pemo.io/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pemo\naid: pemo\nurl: https://www.pemo.io/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Only businesses and individuals conducting a legitimate business activity are eligible to apply for a Pemo\n    account\n- type: individual\n  text: Only businesses and individuals conducting a legitimate business activity are eligible to apply for a Pemo\n    account\nrestricted_uses:\n- summary: Corporate expenses only\n  text: you will only use the Pemo Account and Services for corporate expenses excluding salary payments.\n\
  verification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Until you have submitted, and we have reviewed and approved all required information, your Pemo Account\n    will be available to you on a limited basis only\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pemo/eligibility/pemo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Pemo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Corporate Cards
- Spend Management
- Expense Management
- Accounting Automation
- Invoice Management
- United Arab Emirates
- Saudi Arabia
- Payments
---
