---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: are at least sixteen (16) years old
    value: '16'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You must not access or use the Site from any location prohibited by or subject to comprehensive sanctions
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
name: Honeywell
provenance_date: '2026-11-09'
provider_name: Honeywell
provider_slug: honeywell
slug: honeywell-eligibility
source_date: '2026-11-09'
source_filename: honeywell-eligibility.yml
source_heading: Eligibility
source_page: https://www.honeywell.com/us/en/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Honeywell\naid: honeywell\nurl: https://www.honeywell.com/us/en/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You must not access or use the Site from any location prohibited by or subject to comprehensive sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: are at least sixteen (16) years old\n"
source_yaml_url: https://artifacts.apis.io/honeywell/eligibility/honeywell-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Honeywell's own page on 2026-11-09.
synthetic: false
tags:
- Aerospace
- Building Automation
- Industrial IoT
- Manufacturing
- Fortune 100
- Industrial
- Cybersecurity
---
