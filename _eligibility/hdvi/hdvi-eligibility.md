---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No impersonation of others
    text: You agree to not pretend that you are, or that you represent, someone else, or impersonate any other person or entity.
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
name: HDVI (High Definition Vehicle Insurance)
provenance_date: '2026-11-09'
provider_name: HDVI (High Definition Vehicle Insurance)
provider_slug: hdvi
slug: hdvi-eligibility
source_date: '2026-11-09'
source_filename: hdvi-eligibility.yml
source_heading: Eligibility
source_page: https://hdvi.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HDVI (High Definition Vehicle Insurance)\naid: hdvi\nurl: https://hdvi.com/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No impersonation of others\n  text: You agree to not pretend that you are, or that you represent, someone else, or impersonate any other person\n    or entity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/hdvi/eligibility/hdvi-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from HDVI (High Definition Vehicle Insurance)'s own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Insurtech
- Commercial Trucking
- Fleet Management
- Telematics
- Vehicle Insurance
- Risk Management
---
