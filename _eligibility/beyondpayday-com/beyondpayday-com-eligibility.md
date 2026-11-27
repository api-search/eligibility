---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Beyond Payday is designed for households in the United States, and new account registration is currently limited to the United States.
  entity_types:
  - text: You must be at least 13 years old to create an account.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to create an account.
    value: '13'
  restricted_uses:
  - summary: Embedded calculators on loan/debt sites
    text: your website does not offer loans or debt settlement
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
name: Beyond Payday
provenance_date: '2026-11-09'
provider_name: Beyond Payday
provider_slug: beyondpayday-com
slug: beyondpayday-com-eligibility
source_date: '2026-11-09'
source_filename: beyondpayday-com-eligibility.yml
source_heading: Eligibility
source_page: https://beyondpayday.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beyond Payday\naid: beyondpayday-com\nurl: https://beyondpayday.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Beyond Payday is designed for households in the United States, and new account registration is currently\n    limited to the United States.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to create an account.\nrestricted_uses:\n- summary: Embedded calculators on loan/debt sites\n  text: your website does not offer loans or debt settlement\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: You must be at least 13 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/beyondpayday-com/eligibility/beyondpayday-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beyond Payday's own page on 2026-11-09.
synthetic: false
tags:
- Financial Planning
- Retirement Planning
- Household Budgeting
- Personal Finance
- AI Assistant
- Debt Payoff
- Financial-Tools
---
