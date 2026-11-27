---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Access to the Sites may not be legal by certain persons or in certain countries.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use restricted
    text: You will refrain from using the Site or Site Materials for commercial purposes, unless otherwise authorized by Dayforce in writing.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to create a User Account to access a Site, download Site Materials, register for events, or other purposes that Dayforce, in its sole discretion, requires.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dayforce
provenance_date: '2026-11-09'
provider_name: Dayforce
provider_slug: dayforce
slug: dayforce-eligibility
source_date: '2026-11-09'
source_filename: dayforce-eligibility.yml
source_heading: Eligibility
source_page: https://www.dayforce.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dayforce\naid: dayforce\nurl: https://www.dayforce.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Access to the Sites may not be legal by certain persons or in certain countries.\nentity_types: []\nrestricted_uses:\n- summary: Commercial use restricted\n  text: You will refrain from using the Site or Site Materials for commercial purposes, unless otherwise authorized\n    by Dayforce in writing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to create a User Account to access a Site, download Site Materials, register for\
  \ events,\n    or other purposes that Dayforce, in its sole discretion, requires.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dayforce/eligibility/dayforce-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Dayforce's own page on 2026-11-09.
synthetic: false
tags:
- Company
- HCM
- Payroll
- Workforce Management
- Talent Management
- Analytics
---
