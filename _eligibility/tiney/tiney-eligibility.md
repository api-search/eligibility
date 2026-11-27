---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual you are over eighteen years old or supervised by a parent or guardian
    type: individual
  - text: if you are opening an account on behalf of a company or other business you are authorised by that business to act on its behalf
    type: business
  minimum_age:
    text: if you are an individual you are over eighteen years old or supervised by a parent or guardian
    value: '18'
  restricted_uses:
  - summary: Harm to persons
    text: You must not use our Services in any way, or for any purpose, that is intended to harm any person or persons in any way
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
name: Tiney
provenance_date: '2026-11-10'
provider_name: Tiney
provider_slug: tiney
slug: tiney-eligibility
source_date: '2026-11-10'
source_filename: tiney-eligibility.yml
source_heading: Eligibility
source_page: https://www.tiney.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Tiney\naid: tiney\nurl: https://www.tiney.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual you are over eighteen years old or supervised by a parent or guardian\n- type: business\n  text: if you are opening an account on behalf of a company or other business you are authorised by that business\n    to act on its behalf\nrestricted_uses:\n- summary: Harm to persons\n  text: You must not use our Services in any way, or for any purpose, that is intended to harm any person or persons\n    in any way\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: if you are an individual you are over eighteen years old or supervised by a parent or guardian\n"
source_yaml_url: https://artifacts.apis.io/tiney/eligibility/tiney-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Tiney's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Future Of Work
- Childcare
- Early Years Education
- Childminder Agency
- Marketplace
- United Kingdom
---
