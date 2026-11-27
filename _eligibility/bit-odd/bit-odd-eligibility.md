---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to use our Services.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use our Services.
    value: '13'
  restricted_uses:
  - summary: Commercial use prohibited
    text: Use the Services for any commercial purposes
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
name: BIT ODD
provenance_date: '2026-11-09'
provider_name: BIT ODD
provider_slug: bit-odd
slug: bit-odd-eligibility
source_date: '2026-11-09'
source_filename: bit-odd-eligibility.yml
source_heading: Eligibility
source_page: https://bit-odd.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BIT ODD\naid: bit-odd\nurl: https://bit-odd.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use our Services.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: Use the Services for any commercial purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use our Services.\n"
source_yaml_url: https://artifacts.apis.io/bit-odd/eligibility/bit-odd-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from BIT ODD's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Entertainment
- Gaming
- Mobile Games
- Game Studio
- Finland
---
