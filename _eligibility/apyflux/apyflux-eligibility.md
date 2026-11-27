---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Website can be accessed and used globally.
  entity_types:
  - text: The Website is intended for users who are 18 years of age or older.
    type: individual
  minimum_age:
    text: The Website is intended for users who are 18 years of age or older.
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
name: Apyflux
provenance_date: '2026-11-09'
provider_name: Apyflux
provider_slug: apyflux
slug: apyflux-eligibility
source_date: '2026-11-09'
source_filename: apyflux-eligibility.yml
source_heading: Eligibility
source_page: https://www.apyflux.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apyflux\naid: apyflux\nurl: https://www.apyflux.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Website can be accessed and used globally.\nentity_types:\n- type: individual\n  text: The Website is intended for users who are 18 years of age or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Website is intended for users who are 18 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/apyflux/eligibility/apyflux-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Apyflux's own page on 2026-11-09.
synthetic: false
tags:
- API Marketplace
- Developer Tools
- Integration
- Monetization
- Software-as-a-Service
---
