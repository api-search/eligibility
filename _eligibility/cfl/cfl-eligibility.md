---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services and the contents contained in the Services solely for your own individual non-commercial and informational purposes only.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: Any other use, including for any commercial purposes, is strictly prohibited without our express prior written consent.
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
name: CFL scoreboard JSON
provenance_date: '2026-11-09'
provider_name: CFL scoreboard JSON
provider_slug: cfl
slug: cfl-eligibility
source_date: '2026-11-09'
source_filename: cfl-eligibility.yml
source_heading: Eligibility
source_page: https://cfl.ca/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CFL scoreboard JSON\naid: cfl\nurl: https://cfl.ca/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services and the contents contained in the Services solely for your own individual non-commercial\n    and informational purposes only.\nrestricted_uses:\n- summary: No commercial use\n  text: Any other use, including for any commercial purposes, is strictly prohibited without our express prior written\n    consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/cfl/eligibility/cfl-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from CFL scoreboard JSON's own page on 2026-11-09.
synthetic: false
tags:
- Sports
- Football
- Canada
- Professional League
- Entertainment
---
