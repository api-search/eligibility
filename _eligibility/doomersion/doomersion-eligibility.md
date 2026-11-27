---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 12 years of age to use Doomersion.
    type: individual
  minimum_age:
    text: You must be at least 12 years of age to use Doomersion.
    value: '12'
  restricted_uses:
  - summary: Illegal or harmful use
    text: Use the Service for any illegal purpose or in violation of any laws
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
name: Doomersion
provenance_date: '2026-11-09'
provider_name: Doomersion
provider_slug: doomersion
slug: doomersion-eligibility
source_date: '2026-11-09'
source_filename: doomersion-eligibility.yml
source_heading: Eligibility
source_page: https://doomersion.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doomersion\naid: doomersion\nurl: https://doomersion.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 12 years of age to use Doomersion.\nrestricted_uses:\n- summary: Illegal or harmful use\n  text: Use the Service for any illegal purpose or in violation of any laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '12'\n  text: You must be at least 12 years of age to use Doomersion.\n"
source_yaml_url: https://artifacts.apis.io/doomersion/eligibility/doomersion-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Doomersion's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Language Learning
- EdTech
- Mobile App
- Consumer
- Short-Form Video
- Y Combinator
---
