---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: thepersonorentitythatwill beutilizingtheSatimwebsite
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: illegal activity
    text: (iv)isillegal orencouragesoradvocatesillegal activity
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
name: SATIM
provenance_date: '2026-11-10'
provider_name: SATIM
provider_slug: satim
slug: satim-eligibility
source_date: '2026-11-10'
source_filename: satim-eligibility.yml
source_heading: Eligibility
source_page: https://satim.co/terms-and-conditions.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SATIM\naid: satim\nurl: https://satim.co/terms-and-conditions.pdf\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: thepersonorentitythatwill beutilizingtheSatimwebsite\nrestricted_uses:\n- summary: illegal activity\n  text: (iv)isillegal orencouragesoradvocatesillegal activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/satim/eligibility/satim-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from SATIM's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Defense
- Intelligence
- Geospatial
- Synthetic Aperture Radar
- Satellite Imagery
- Artificial Intelligence
- ISR
- Remote Sensing
---
