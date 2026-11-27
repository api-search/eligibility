---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: ASCAP makes no representation that the Services are appropriate or available for use outside the U.S.
  entity_types:
  - text: it applies to all individuals, including ASCAP members, who use our products and services
    type: individual
  minimum_age:
    text: you are 13 years of age or older (if you are located in the United States) or 16 years of age or older (if you are located outside of the United States).
    value: '13'
  restricted_uses:
  - summary: Non-commercial personal use only
    text: non-commercial and limited personal use and for no other purposes
  - summary: No AI training or dataset development without consent
    text: without the express, prior written consent of ASCAP (which may be withheld in ASCAP’s sole and absolute discretion)
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
name: ASCAP
provenance_date: '2026-11-09'
provider_name: ASCAP
provider_slug: ascap
slug: ascap-eligibility
source_date: '2026-11-09'
source_filename: ascap-eligibility.yml
source_heading: Eligibility
source_page: https://www.ascap.com/help/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ASCAP\naid: ascap\nurl: https://www.ascap.com/help/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: ASCAP makes no representation that the Services are appropriate or available for use outside the U.S.\nentity_types:\n- type: individual\n  text: it applies to all individuals, including ASCAP members, who use our products and services\nrestricted_uses:\n- summary: Non-commercial personal use only\n  text: non-commercial and limited personal use and for no other purposes\n- summary: No AI training or dataset development without consent\n  text: without the express,\
  \ prior written consent of ASCAP (which may be withheld in ASCAP’s sole and absolute\n    discretion)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are 13 years of age or older (if you are located in the United States) or 16 years of age or older (if\n    you are located outside of the United States).\n"
source_yaml_url: https://artifacts.apis.io/ascap/eligibility/ascap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from ASCAP's own page on 2026-11-09.
synthetic: false
tags:
- Music
- Licensing
- Royalties
- Non-Profit
- Creators
---
