---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You promise to us you are old enough to enter legally binding contracts through this Website
    type: individual
  minimum_age:
    text: You promise to us you are old enough to enter legally binding contracts through this Website
    value: null
  restricted_uses:
  - summary: Personal non-commercial use only
    text: You agree to use the Website only for personal, non-commercial use.
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
name: Emirates
provenance_date: '2026-11-09'
provider_name: Emirates
provider_slug: emirates
slug: emirates-eligibility
source_date: '2026-11-09'
source_filename: emirates-eligibility.yml
source_heading: Eligibility
source_page: https://www.emirates.com/english/information/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Emirates\naid: emirates\nurl: https://www.emirates.com/english/information/terms-and-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You promise to us you are old enough to enter legally binding contracts through this Website\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: You agree to use the Website only for personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You promise to us you are old enough to\
  \ enter legally binding contracts through this Website\n"
source_yaml_url: https://artifacts.apis.io/emirates/eligibility/emirates-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Emirates's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Airlines
- Travel
- Aviation
- Dubai
---
