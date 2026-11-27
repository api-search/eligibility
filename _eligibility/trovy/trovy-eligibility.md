---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Trovy Site is made available only for personal, non-commercial use and display by U.S. residents legally capable of entering commercial agreements.
  entity_types:
  - text: You may only accept this Agreement and use the Trovy Site if you are legally authorized to accept and be bound by these terms and of a legal age to enter this Agreement.
    type: individual
  minimum_age:
    text: of a legal age to enter this Agreement
    value: null
  restricted_uses:
  - summary: Commercial use prohibited
    text: The Trovy Site is made available only for personal, non-commercial use and display
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
name: Trovy
provenance_date: '2026-11-10'
provider_name: Trovy
provider_slug: trovy
slug: trovy-eligibility
source_date: '2026-11-10'
source_filename: trovy-eligibility.yml
source_heading: Eligibility
source_page: https://trovy.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Trovy\naid: trovy\nurl: https://trovy.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Trovy Site is made available only for personal, non-commercial use and display by U.S. residents legally\n    capable of entering commercial agreements.\nentity_types:\n- type: individual\n  text: You may only accept this Agreement and use the Trovy Site if you are legally authorized to accept and be\n    bound by these terms and of a legal age to enter this Agreement.\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: The Trovy Site is made available only\
  \ for personal, non-commercial use and display\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: of a legal age to enter this Agreement\n"
source_yaml_url: https://artifacts.apis.io/trovy/eligibility/trovy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Trovy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- HELOC
- Home Equity
- Credit Cards
- Lending
- Consumer Finance
---
