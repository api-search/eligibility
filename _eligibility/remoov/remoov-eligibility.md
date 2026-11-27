---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: an individual or the entity entering into the Decluttering Agreement
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Prohibited item types
    text: Remoov does not accept weapons, hazardous waste (including paint and aerosols), illegal items (including banned drugs, contraband trade items) or items which the Customer does not legally own.
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
name: Remoov
provenance_date: '2026-11-10'
provider_name: Remoov
provider_slug: remoov
slug: remoov-eligibility
source_date: '2026-11-10'
source_filename: remoov-eligibility.yml
source_heading: Eligibility
source_page: https://remoovit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Remoov\naid: remoov\nurl: https://remoovit.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: an individual or the entity entering into the Decluttering Agreement\nrestricted_uses:\n- summary: Prohibited item types\n  text: Remoov does not accept weapons, hazardous waste (including paint and aerosols), illegal items (including\n    banned drugs, contraband trade items) or items which the Customer does not legally own.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/remoov/eligibility/remoov-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Remoov's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Junk Removal
- Furniture Resale
- Consignment
- Recycling
- Donation
- Home Services
- Decluttering
- Moving
- Sustainability
---
