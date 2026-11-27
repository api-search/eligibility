---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: YOU MUST BE AND HEREBY AFFIRM THAT YOU ARE AN ADULT OF THE LEGAL AGE OF MAJORITY IN YOUR COUNTRY OR STATE OF RESIDENCE.
    type: individual
  minimum_age:
    text: you are at least 13 years old, or else you must not use our Services.
    value: '13'
  restricted_uses:
  - summary: No commercial use of Services
    text: (a) any commercial use of the Services, or the Materials therein
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
name: King
provenance_date: '2026-11-09'
provider_name: King
provider_slug: king-com
slug: king-com-eligibility
source_date: '2026-11-09'
source_filename: king-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.king.com/termsAndConditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: King\naid: king-com\nurl: https://www.king.com/termsAndConditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: YOU MUST BE AND HEREBY AFFIRM THAT YOU ARE AN ADULT OF THE LEGAL AGE OF MAJORITY IN YOUR COUNTRY OR STATE\n    OF RESIDENCE.\nrestricted_uses:\n- summary: No commercial use of Services\n  text: (a) any commercial use of the Services, or the Materials therein\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are at least 13 years\
  \ old, or else you must not use our Services.\n"
source_yaml_url: https://artifacts.apis.io/king-com/eligibility/king-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from King's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Gaming
- Casual Games
- Mobile
- Online
---
