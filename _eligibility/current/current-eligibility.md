---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Only individuals 18 years or older who can form a legally binding contract can use our Services
    type: individual
  minimum_age:
    text: Only individuals 18 years or older who can form a legally binding contract can use our Services
    value: '18'
  restricted_uses:
  - summary: Anonymizing proxy
    text: You agree to not use an anonymizing proxy.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: As part of Account opening, you may be prompted to provide your name, date of birth, address, phone number, Social Security number, and your government-issued identification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Current
provenance_date: '2026-11-09'
provider_name: Current
provider_slug: current
slug: current-eligibility
source_date: '2026-11-09'
source_filename: current-eligibility.yml
source_heading: Eligibility
source_page: https://current.com/terms_of_service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Current\naid: current\nurl: https://current.com/terms_of_service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Only individuals 18 years or older who can form a legally binding contract can use our Services\nrestricted_uses:\n- summary: Anonymizing proxy\n  text: You agree to not use an anonymizing proxy.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: As part of Account opening, you may be prompted to provide your name, date of birth, address, phone number,\n    Social Security number, and your government-issued\
  \ identification.\nminimum_age:\n  value: '18'\n  text: Only individuals 18 years or older who can form a legally binding contract can use our Services\n"
source_yaml_url: https://artifacts.apis.io/current/eligibility/current-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Current's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Neobank
- Consumer Banking
- Personal Finance
- Payments
- Credit Building
- Savings
- Mobile Banking
- United States
- Open Finance
- Aggregator Access
---
