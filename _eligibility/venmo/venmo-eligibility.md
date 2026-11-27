---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be in the United States and have a U.S. bank account to use the Venmo services.
  entity_types:
  - text: To create a personal account, you must be a resident of the United States or one of its territories, be at least 18 years old or the age of majority in your state of residence
    type: individual
  - text: If you create a business profile for a business legal entity (instead of opening a business profile on behalf of an unincorporated business/sole proprietorship), you agree that you are a legal representative of that business
    type: business
  minimum_age:
    text: be at least 18 years old or the age of majority in your state of residence
    value: '18'
  restricted_uses:
  - summary: Peer-to-peer goods and services
    text: PAYING OR RECEIVING PAYMENT FOR A GOOD OR A SERVICE IS PROHIBITED.
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
name: Venmo
provenance_date: '2026-11-10'
provider_name: Venmo
provider_slug: venmo
slug: venmo-eligibility
source_date: '2026-11-10'
source_filename: venmo-eligibility.yml
source_heading: Eligibility
source_page: https://venmo.com/legal/us-user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Venmo\naid: venmo\nurl: https://venmo.com/legal/us-user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be in the United States and have a U.S. bank account to use the Venmo services.\nentity_types:\n- type: individual\n  text: To create a personal account, you must be a resident of the United States or one of its territories, be\n    at least 18 years old or the age of majority in your state of residence\n- type: business\n  text: If you create a business profile for a business legal entity (instead of opening a business profile on behalf\n\
  \    of an unincorporated business/sole proprietorship), you agree that you are a legal representative of that business\nrestricted_uses:\n- summary: Peer-to-peer goods and services\n  text: PAYING OR RECEIVING PAYMENT FOR A GOOD OR A SERVICE IS PROHIBITED.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: be at least 18 years old or the age of majority in your state of residence\n"
source_yaml_url: https://artifacts.apis.io/venmo/eligibility/venmo-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Venmo's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Payments
- Fintech
- Mobile Payments
- P2P Payments
- Money Transfer
- Digital Wallet
---
