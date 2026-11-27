---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are a natural person and of eighteen (18) years of age or older, or otherwise the age of majority in your jurisdiction
    type: individual
  minimum_age:
    text: The Site and the App are offered only to users eighteen (18) years of age or older, or otherwise the age of majority in their respective jurisdictions
    value: '18'
  restricted_uses:
  - summary: Lawful use only
    text: you may only use them for lawful purposes
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
name: FirstVet
provenance_date: '2026-11-09'
provider_name: FirstVet
provider_slug: firstvet
slug: firstvet-eligibility
source_date: '2026-11-09'
source_filename: firstvet-eligibility.yml
source_heading: Eligibility
source_page: https://firstvet.com/us/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FirstVet\naid: firstvet\nurl: https://firstvet.com/us/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are a natural person and of eighteen (18) years of age or older, or otherwise the age of majority in\n    your jurisdiction\nrestricted_uses:\n- summary: Lawful use only\n  text: you may only use them for lawful purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site and the App are offered only to users eighteen\
  \ (18) years of age or older, or otherwise the age\n    of majority in their respective jurisdictions\n"
source_yaml_url: https://artifacts.apis.io/firstvet/eligibility/firstvet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from FirstVet's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Veterinary
- Telehealth
- Pet Care
- Health
- Sweden
---
