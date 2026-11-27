---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - EU
    - IS
    - LI
    - 'NO'
    served: []
    text: AncestralFire is not offered to people in the European Union, Iceland, Liechtenstein or Norway for now.
  minimum_age:
    text: AncestralFire is for people 13 and older. If you are younger, ask a parent or guardian to use it with you.
    value: '13'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account to use it.
excluded_countries:
- EU
- IS
- LI
- 'NO'
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AncestralFire
provenance_date: '2026-11-09'
provider_name: AncestralFire
provider_slug: ancestral-fire-com
slug: ancestral-fire-com-eligibility
source_date: '2026-11-09'
source_filename: ancestral-fire-com-eligibility.yml
source_heading: Eligibility
source_page: https://ancestral-fire.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AncestralFire\naid: ancestral-fire-com\nurl: https://ancestral-fire.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - EU\n  - IS\n  - LI\n  - 'NO'\n  text: AncestralFire is not offered to people in the European Union, Iceland, Liechtenstein or Norway for now.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need an account to use it.\nminimum_age:\n  value: '13'\n  text: AncestralFire is for people 13 and older. If you are younger, ask a parent or guardian to use it with you.\n"
source_yaml_url: https://artifacts.apis.io/ancestral-fire-com/eligibility/ancestral-fire-com-eligibility.yml
stated_fields:
- countries
- verification
- minimum_age
summary_line: 3 quoted statements, read from AncestralFire's own page on 2026-11-09.
synthetic: false
tags:
- Genealogy
- Family Tree
- Ancestry
- Artificial Intelligence
- History
---
