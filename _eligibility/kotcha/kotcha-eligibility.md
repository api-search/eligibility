---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not located in countries subject to U.S. Government embargoes or designated as terrorist-supporting.
  entity_types:
  - text: Users must be 18 or older; accounts for underage users may be deleted.
    type: individual
  minimum_age:
    text: Users must be 18 or older
    value: '18'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: Users may use the Site and Apps for personal, non-commercial purposes only in compliance with applicable laws.
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
name: Kotcha
provenance_date: '2026-11-09'
provider_name: Kotcha
provider_slug: kotcha
slug: kotcha-eligibility
source_date: '2026-11-09'
source_filename: kotcha-eligibility.yml
source_heading: Eligibility
source_page: https://www.kotcha.com/en/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kotcha\naid: kotcha\nurl: https://www.kotcha.com/en/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not located in countries subject to U.S. Government embargoes or designated as terrorist-supporting.\nentity_types:\n- type: individual\n  text: Users must be 18 or older; accounts for underage users may be deleted.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: Users may use the Site and Apps for personal, non-commercial purposes only in compliance with applicable\n    laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: Users must be 18 or older\n"
source_yaml_url: https://artifacts.apis.io/kotcha/eligibility/kotcha-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Kotcha's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sporttech
- Running
- Fitness
- Health
- Coaching
- Artificial Intelligence
- Mobile App
- Wearables
- Consumer
---
