---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Customer is not permitted to avail Wallet Services for any regulatory reason.
  entity_types:
  - text: The Account Administrator handling the registration process must be at least 18 years old and adequately authorised to open an Account for the use of the Wallet Services.
    type: individual
  minimum_age:
    text: The Account Administrator handling the registration process must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Gaming, cryptocurrency and virtual currency payments
    text: prohibition of certain categories of transactions for example payments in relation to gaming, cryptocurrencies and all other virtual currencies by specifying these on the Customer Portal or the App.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: The Account Administrator and any Team Budget Manager must complete the verification process required by SiFi.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: SiFi
provenance_date: '2026-11-10'
provider_name: SiFi
provider_slug: sifi
slug: sifi-eligibility
source_date: '2026-11-10'
source_filename: sifi-eligibility.yml
source_heading: Eligibility
source_page: https://www.sifi.app/en/legal/terms-and-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SiFi\naid: sifi\nurl: https://www.sifi.app/en/legal/terms-and-conditions/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Customer is not permitted to avail Wallet Services for any regulatory reason.\nentity_types:\n- type: individual\n  text: The Account Administrator handling the registration process must be at least 18 years old and adequately\n    authorised to open an Account for the use of the Wallet Services.\nrestricted_uses:\n- summary: Gaming, cryptocurrency and virtual currency payments\n  text: prohibition of certain categories of transactions for example payments\
  \ in relation to gaming, cryptocurrencies\n    and all other virtual currencies by specifying these on the Customer Portal or the App.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: The Account Administrator and any Team Budget Manager must complete the verification process required by\n    SiFi.\nminimum_age:\n  value: '18'\n  text: The Account Administrator handling the registration process must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/sifi/eligibility/sifi-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from SiFi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Spend Management
- Corporate Cards
- Expense Management
- Payments
- Saudi Arabia
- Business
---
