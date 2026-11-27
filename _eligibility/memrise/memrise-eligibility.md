---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: worldwide and non-exclusive licence
  entity_types:
  - text: We only provide our site for consumer private use.
    type: individual
  minimum_age:
    text: you are at least 13 years old
    value: '13'
  restricted_uses:
  - summary: Commercial or business purposes
    text: You agree not to use our site for any commercial or business purposes
  - summary: Registering accounts for others
    text: Be used to register for an Account for anyone other than yourself
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
name: memrise
provenance_date: '2026-11-10'
provider_name: memrise
provider_slug: memrise
slug: memrise-eligibility
source_date: '2026-11-10'
source_filename: memrise-eligibility.yml
source_heading: Eligibility
source_page: https://www.memrise.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: memrise\naid: memrise\nurl: https://www.memrise.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: worldwide and non-exclusive licence\nentity_types:\n- type: individual\n  text: We only provide our site for consumer private use.\nrestricted_uses:\n- summary: Commercial or business purposes\n  text: You agree not to use our site for any commercial or business purposes\n- summary: Registering accounts for others\n  text: Be used to register for an Account for anyone other than yourself\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: you are at least 13 years old\n"
source_yaml_url: https://artifacts.apis.io/memrise/eligibility/memrise-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from memrise's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Language Learning
- Education
- EdTech
- Mobile App
- Consumer
- Artificial Intelligence
---
