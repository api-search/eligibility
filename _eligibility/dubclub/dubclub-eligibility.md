---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Platform for use by persons located in the United States who can legally enter into these Terms and are at least eighteen (18) years old.
  entity_types:
  - text: We provide the Platform for use by persons located in the United States who can legally enter into these Terms and are at least eighteen (18) years old.
    type: individual
  minimum_age:
    text: at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: No wagering with DBX
    text: DBX may not be used to place, fund, or settle any wager, bet, or other gambling transaction, whether on the Platform or on any third-party sportsbook, casino, or similar service.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Your phone number is your username. To login to your account , a verification code is texted to your phone.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: DubClub
provenance_date: '2026-11-09'
provider_name: DubClub
provider_slug: dubclub
slug: dubclub-eligibility
source_date: '2026-11-09'
source_filename: dubclub-eligibility.yml
source_heading: Eligibility
source_page: https://dubclub.win/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DubClub\naid: dubclub\nurl: https://dubclub.win/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Platform for use by persons located in the United States who can legally enter into these\n    Terms and are at least eighteen (18) years old.\nentity_types:\n- type: individual\n  text: We provide the Platform for use by persons located in the United States who can legally enter into these\n    Terms and are at least eighteen (18) years old.\nrestricted_uses:\n- summary: No wagering with DBX\n  text: DBX may not be used to place, fund, or settle any\
  \ wager, bet, or other gambling transaction, whether on\n    the Platform or on any third-party sportsbook, casino, or similar service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Your phone number is your username. To login to your account , a verification code is texted to your phone.\nminimum_age:\n  value: '18'\n  text: at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/dubclub/eligibility/dubclub-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from DubClub's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Sports Betting
- Creator Economy
- Monetization
- Subscription
- Messaging
- Sports
- Community
---
