---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    - GB
    - CA
    - BH
    text: In order to use the Services, you must be a resident of the United States, the United Kingdom, the European Union, Canada or the Kingdom of Bahrain.
  entity_types:
  - text: The Services allow consumers (“ Users ”) to withdraw and earn funds
    type: individual
  minimum_age:
    text: In order to use the full suite of Services – including to create an Account (defined below) – you must be eighteen (18) years of age or older.
    value: '18'
  restricted_uses:
  - summary: Gift card restrictions
    text: Gift Cards cannot be used to purchase other gift cards, reloaded, resold, used for unauthorized marketing, sweepstakes, advertising, or other promotional purposes
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
name: Prizeout
provenance_date: '2026-11-10'
provider_name: Prizeout
provider_slug: prizeout
slug: prizeout-eligibility
source_date: '2026-11-10'
source_filename: prizeout-eligibility.yml
source_heading: Eligibility
source_page: https://www.prizeout.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prizeout\naid: prizeout\nurl: https://www.prizeout.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  - GB\n  - CA\n  - BH\n  excluded: []\n  text: In order to use the Services, you must be a resident of the United States, the United Kingdom, the European\n    Union, Canada or the Kingdom of Bahrain.\nentity_types:\n- type: individual\n  text: The Services allow consumers (“ Users ”) to withdraw and earn funds\nrestricted_uses:\n- summary: Gift card restrictions\n  text: Gift Cards cannot be used to purchase other gift cards, reloaded, resold, used for unauthorized marketing,\n    sweepstakes,\
  \ advertising, or other promotional purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: In order to use the full suite of Services – including to create an Account (defined below) – you must be\n    eighteen (18) years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/prizeout/eligibility/prizeout-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Prizeout's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Advertising
- Rewards
- Gift Cards
- Payouts
- Financial Services
- Credit Union
- Banking
- Loyalty
- Embedded Finance
- AdTech
- Fintech
---
