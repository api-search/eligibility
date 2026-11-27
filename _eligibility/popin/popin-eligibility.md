---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual user of at least 13 years of age
    type: individual
  minimum_age:
    text: The pop.in Service is not available to persons under the age of 13.
    value: '13'
  restricted_uses:
  - summary: No illegal or harmful use
    text: use the pop.in Service for any illegal purpose, or in violation of any local, state, national, or international law
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
name: Pop.in
provenance_date: '2026-11-10'
provider_name: Pop.in
provider_slug: popin
slug: popin-eligibility
source_date: '2026-11-10'
source_filename: popin-eligibility.yml
source_heading: Eligibility
source_page: https://pop.in/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pop.in\naid: popin\nurl: https://pop.in/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual user of at least 13 years of age\nrestricted_uses:\n- summary: No illegal or harmful use\n  text: use the pop.in Service for any illegal purpose, or in violation of any local, state, national, or international\n    law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The pop.in Service is not available to persons under the age of 13.\n"
source_yaml_url: https://artifacts.apis.io/popin/eligibility/popin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Pop.in's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Social
- Gaming
- Multiplayer
- Mobile
- Consumer
- Entertainment
---
