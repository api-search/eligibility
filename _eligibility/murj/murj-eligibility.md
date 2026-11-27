---
claim_count: 1
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
  - summary: Healthcare compliance
    text: A Business Associate Agreement must be executed by and between the parties for this Agreement to become effective.
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
name: Murj
provenance_date: '2026-11-10'
provider_name: Murj
provider_slug: murj
slug: murj-eligibility
source_date: '2026-11-10'
source_filename: murj-eligibility.yml
source_heading: Eligibility
source_page: https://murj.com/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Murj\naid: murj\nurl: https://murj.com/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Healthcare compliance\n  text: A Business Associate Agreement must be executed by and between the parties for this Agreement to become\n    effective.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/murj/eligibility/murj-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Murj's own page on 2026-11-10.
synthetic: false
tags:
- Cardiac Device Management
- Remote Patient Monitoring
- Heart Failure Monitoring
- Ambulatory Cardiac Monitoring
- Pulmonary Artery Pressure Monitoring
- Clinical Services
---
