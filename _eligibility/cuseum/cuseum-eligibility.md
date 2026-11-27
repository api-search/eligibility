---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual, legally competent and over the age of 18 years
    type: individual
  - text: you possess the legal right and ability to enter into this Agreement
    type: other
  minimum_age:
    text: You represent and warrant that you are at least 13 years of age
    value: '13'
  restricted_uses:
  - summary: Commercial activities
    text: not to use the Services to engage in commercial activities without our express written permission
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
name: Cuseum
provenance_date: '2026-11-09'
provider_name: Cuseum
provider_slug: cuseum
slug: cuseum-eligibility
source_date: '2026-11-09'
source_filename: cuseum-eligibility.yml
source_heading: Eligibility
source_page: https://cuseum.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cuseum\naid: cuseum\nurl: https://cuseum.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual, legally competent and over the age of 18 years\n- type: other\n  text: you possess the legal right and ability to enter into this Agreement\nrestricted_uses:\n- summary: Commercial activities\n  text: not to use the Services to engage in commercial activities without our express written permission\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ '13'\n  text: You represent and warrant that you are at least 13 years of age\n"
source_yaml_url: https://artifacts.apis.io/cuseum/eligibility/cuseum-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cuseum's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Museums
- Cultural Institutions
- Non-Profit
- Digital Membership
- Mobile Wallet
- Apple Wallet
- Google Wallet
- Member Engagement
- Audio Guides
- Ticketing
- CRM Integration
---
