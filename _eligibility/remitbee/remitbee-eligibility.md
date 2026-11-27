---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: Money transfers are sent from Canada to eligible countries worldwide. Currency exchange services are currently limited to residents of Canada.
  entity_types:
  - text: To register for a Remitbee account, you must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher.
    type: individual
  - text: Business accounts are intended for use by corporations, partnerships, sole proprietorships, and nonprofit organizations
    type: business
  minimum_age:
    text: you must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher.
    value: '18'
  restricted_uses:
  - summary: Personal PAD only; no third-party payment accounts
    text: Payments made using third-party bank accounts, debit cards, or credit cards are strictly prohibited.
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
name: Remitbee
provenance_date: '2026-11-10'
provider_name: Remitbee
provider_slug: remitbee
slug: remitbee-eligibility
source_date: '2026-11-10'
source_filename: remitbee-eligibility.yml
source_heading: Eligibility
source_page: https://www.remitbee.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Remitbee\naid: remitbee\nurl: https://www.remitbee.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: Money transfers are sent from Canada to eligible countries worldwide. Currency exchange services are currently\n    limited to residents of Canada.\nentity_types:\n- type: individual\n  text: To register for a Remitbee account, you must be at least 18 years old or the age of majority in your jurisdiction,\n    whichever is higher.\n- type: business\n  text: Business accounts are intended for use by corporations, partnerships, sole proprietorships,\
  \ and nonprofit\n    organizations\nrestricted_uses:\n- summary: Personal PAD only; no third-party payment accounts\n  text: Payments made using third-party bank accounts, debit cards, or credit cards are strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old or the age of majority in your jurisdiction, whichever is higher.\n"
source_yaml_url: https://artifacts.apis.io/remitbee/eligibility/remitbee-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Remitbee's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Money Transfer
- Remittances
- Foreign Exchange
- Payments
- Fintech
- Cross-Border Payments
- Mobile Top-Up
- Bill Payments
- Canada
---
