---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may access and use the Site solely for your personal, non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Non-commercial personal use only
    text: You may access and use the Site solely for your personal, non-commercial use.
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
name: Dash Bio
provenance_date: '2026-11-09'
provider_name: Dash Bio
provider_slug: dash-bio
slug: dash-bio-eligibility
source_date: '2026-11-09'
source_filename: dash-bio-eligibility.yml
source_heading: Eligibility
source_page: https://www.dash.bio/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dash Bio\naid: dash-bio\nurl: https://www.dash.bio/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may access and use the Site solely for your personal, non-commercial use.\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: You may access and use the Site solely for your personal, non-commercial use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dash-bio/eligibility/dash-bio-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dash Bio's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Bioanalysis
- CRO
- Automation
- Artificial Intelligence
---
