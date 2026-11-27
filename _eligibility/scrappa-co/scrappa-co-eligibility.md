---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service
    type: individual
  - text: One person or entity may not maintain more than one account
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use the Service for any illegal purpose or in violation of any laws
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
name: scrappa-co
provenance_date: '2026-11-10'
provider_name: scrappa-co
provider_slug: scrappa-co
slug: scrappa-co-eligibility
source_date: '2026-11-10'
source_filename: scrappa-co-eligibility.yml
source_heading: Eligibility
source_page: https://scrappa.co/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: scrappa-co\naid: scrappa-co\nurl: https://scrappa.co/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service\n- type: business\n  text: One person or entity may not maintain more than one account\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the Service for any illegal purpose or in violation of any laws\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years\
  \ old to use the Service\n"
source_yaml_url: https://artifacts.apis.io/scrappa-co/eligibility/scrappa-co-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from scrappa-co's own page on 2026-11-10.
synthetic: false
tags:
- Web Scraping
- Data API
- Search
- Automation
- JSON
---
