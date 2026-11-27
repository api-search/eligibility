---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: ClearGov makes no representation that any Content on the Service is appropriate or available for use in other locations.
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial use only
    text: You may use the Service solely for personal and non-commercial purposes.
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
name: ClearGov
provenance_date: '2026-11-09'
provider_name: ClearGov
provider_slug: cleargov
slug: cleargov-eligibility
source_date: '2026-11-09'
source_filename: cleargov-eligibility.yml
source_heading: Eligibility
source_page: https://cleargov.com/assets/ClearGov.com-Terms-of-Service.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ClearGov\naid: cleargov\nurl: https://cleargov.com/assets/ClearGov.com-Terms-of-Service.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: ClearGov makes no representation that any Content on the Service is appropriate or available for use in\n    other locations.\nentity_types: []\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You may use the Service solely for personal and non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cleargov/eligibility/cleargov-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 2 quoted statements, read from ClearGov's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Software-as-a-Service
- Government
- Transparency
---
