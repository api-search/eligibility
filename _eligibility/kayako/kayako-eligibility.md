---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site and its contents may only be accessed for personal use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial or resale use
    text: No material from ESW or any website owned, operated, licensed or controlled by ESW may be used for any commercial or resale purposes.
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
name: Kayako
provenance_date: '2026-11-09'
provider_name: Kayako
provider_slug: kayako
slug: kayako-eligibility
source_date: '2026-11-09'
source_filename: kayako-eligibility.yml
source_heading: Eligibility
source_page: https://kayako.com/about/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kayako\naid: kayako\nurl: https://kayako.com/about/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site and its contents may only be accessed for personal use.\nrestricted_uses:\n- summary: Commercial or resale use\n  text: No material from ESW or any website owned, operated, licensed or controlled by ESW may be used for any commercial\n    or resale purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kayako/eligibility/kayako-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Kayako's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Customer Service
- Artificial Intelligence
- Software-as-a-Service
- Help Desk
---
