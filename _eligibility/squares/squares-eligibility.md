---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old and able to form a legally binding contract.
    type: individual
  minimum_age:
    text: You must be at least 18 years old and able to form a legally binding contract.
    value: '18'
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
name: Squares
provenance_date: '2026-11-10'
provider_name: Squares
provider_slug: squares
slug: squares-eligibility
source_date: '2026-11-10'
source_filename: squares-eligibility.yml
source_heading: Eligibility
source_page: https://squares.kz/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Squares\naid: squares\nurl: https://squares.kz/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old and able to form a legally binding contract.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old and able to form a legally binding contract.\n"
source_yaml_url: https://artifacts.apis.io/squares/eligibility/squares-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Squares's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Workspace
- Co-Working
- Travel
- Booking
- Real Estate
---
