---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Be a legal resident of the United States
  entity_types:
  - text: Be at least 18 years old (or the age of majority in your state, if higher)
    type: individual
  minimum_age:
    text: Be at least 18 years old (or the age of majority in your state, if higher)
    value: '18'
  restricted_uses:
  - summary: Prohibited uses
    text: Attempt to obtain a loan using another person's identity or information
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We are not responsible for verifying the accuracy of the information you provide. Lenders independently verify your information as part of their own underwriting process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: LendUp
provenance_date: '2026-11-09'
provider_name: LendUp
provider_slug: lendup
slug: lendup-eligibility
source_date: '2026-11-09'
source_filename: lendup-eligibility.yml
source_heading: Eligibility
source_page: https://www.lendup.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LendUp\naid: lendup\nurl: https://www.lendup.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Be a legal resident of the United States\nentity_types:\n- type: individual\n  text: Be at least 18 years old (or the age of majority in your state, if higher)\nrestricted_uses:\n- summary: Prohibited uses\n  text: Attempt to obtain a loan using another person's identity or information\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We are not responsible for verifying the accuracy of the information you provide. Lenders independently\n    verify\
  \ your information as part of their own underwriting process.\nminimum_age:\n  value: '18'\n  text: Be at least 18 years old (or the age of majority in your state, if higher)\n"
source_yaml_url: https://artifacts.apis.io/lendup/eligibility/lendup-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from LendUp's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Consumer Lending
- Fintech
- Financial Services
- Personal Loans
- Lead Generation
- Defunct
---
