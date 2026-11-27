---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: In Australia, contact Gambling Help Online on 1800 858 858 or visit gamblinghelponline.org.au .
  entity_types:
  - text: You must be at least 18 years old to use BetBank.ai.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use BetBank.ai.
    value: '18'
  restricted_uses:
  - summary: Self-excluded persons
    text: You may not use BetBank.ai if you are excluded from gambling under a self-exclusion scheme, including BetStop, the National Self-Exclusion Register.
  - summary: Bookmaker trading or pricing staff
    text: You also may not use it if you work for, or act on behalf of, a bookmaker or wagering operator in a trading, pricing or risk role, unless we have agreed to it in writing.
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
name: BetBank
provenance_date: '2026-11-09'
provider_name: BetBank
provider_slug: betbank-ai
slug: betbank-ai-eligibility
source_date: '2026-11-09'
source_filename: betbank-ai-eligibility.yml
source_heading: Eligibility
source_page: https://betbank.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: BetBank\naid: betbank-ai\nurl: https://betbank.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: In Australia, contact Gambling Help Online on 1800 858 858 or visit gamblinghelponline.org.au .\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use BetBank.ai.\nrestricted_uses:\n- summary: Self-excluded persons\n  text: You may not use BetBank.ai if you are excluded from gambling under a self-exclusion scheme, including BetStop,\n    the National Self-Exclusion Register.\n- summary: Bookmaker trading or pricing staff\n  text: You also may\
  \ not use it if you work for, or act on behalf of, a bookmaker or wagering operator in a trading,\n    pricing or risk role, unless we have agreed to it in writing.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use BetBank.ai.\n"
source_yaml_url: https://artifacts.apis.io/betbank-ai/eligibility/betbank-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from BetBank's own page on 2026-11-09.
synthetic: false
tags:
- Sports Betting
- Analytics
- Arbitrage
- Odds Comparison
- Australian
---
