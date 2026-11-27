---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Your acceptance of this agreement constitutes a binding commitment by you and any entity you represent to adhere to the terms set forth herein
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: The user agrees to use the Dubb platform solely for lawful purposes and in accordance with these terms and conditions.
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Dubb reserves the right to refuse registration, suspend or cancel accounts, at its sole discretion and without justification
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Dubb
provenance_date: '2026-11-09'
provider_name: Dubb
provider_slug: dubb
slug: dubb-eligibility
source_date: '2026-11-09'
source_filename: dubb-eligibility.yml
source_heading: Eligibility
source_page: https://dubb.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dubb\naid: dubb\nurl: https://dubb.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Your acceptance of this agreement constitutes a binding commitment by you and any entity you represent to\n    adhere to the terms set forth herein\nrestricted_uses:\n- summary: Lawful use only\n  text: The user agrees to use the Dubb platform solely for lawful purposes and in accordance with these terms and\n    conditions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Dubb reserves the right to refuse registration,\
  \ suspend or cancel accounts, at its sole discretion and without\n    justification\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dubb/eligibility/dubb-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from Dubb's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
