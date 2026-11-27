---
claim_count: 7
description: ''
doc:
  countries:
    excluded:
    - US
    - CU
    - SY
    - IR
    - KP
    served: []
    text: Prohibited Jurisdiction shall mean (i) the United States, Cuba, Syria, Iran, North Korea
  entity_types:
  - text: you are at least 18 years old or of legal age to form a binding contract under applicable law
    type: individual
  - text: if you are entering into these Terms on behalf of a legal entity of which you are an employee or agent, you have all necessary rights and authority to bind such legal entity
    type: business
  minimum_age:
    text: you are at least 18 years old or of legal age to form a binding contract under applicable law
    value: '18'
  restricted_uses:
  - summary: No resale or commercial use
    text: use the Services for resale or commercial purposes, including transactions on behalf of other persons or entities
  - summary: US Persons not permitted
    text: you are not a US Person
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: we will ask for your name, physical address, mailing address, date of birth, and other information, and documents that will allow us to identify you in line with the KYC/AML & CTF Policy.
excluded_countries:
- US
- CU
- SY
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PowerTrade
provenance_date: '2026-11-10'
provider_name: PowerTrade
provider_slug: powertrade
slug: powertrade-eligibility
source_date: '2026-11-10'
source_filename: powertrade-eligibility.yml
source_heading: Eligibility
source_page: https://support.power.trade/legal/legal-and-privacy-policies/terms-of-service.md
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PowerTrade\naid: powertrade\nurl: https://support.power.trade/legal/legal-and-privacy-policies/terms-of-service.md\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - US\n  - CU\n  - SY\n  - IR\n  - KP\n  text: Prohibited Jurisdiction shall mean (i) the United States, Cuba, Syria, Iran, North Korea\nentity_types:\n- type: individual\n  text: you are at least 18 years old or of legal age to form a binding contract under applicable law\n- type: business\n  text: if you are entering into these Terms on behalf of a legal entity of which you are an employee or agent,\n    you\
  \ have all necessary rights and authority to bind such legal entity\nrestricted_uses:\n- summary: No resale or commercial use\n  text: use the Services for resale or commercial purposes, including transactions on behalf of other persons or\n    entities\n- summary: US Persons not permitted\n  text: you are not a US Person\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: we will ask for your name, physical address, mailing address, date of birth, and other information, and\n    documents that will allow us to identify you in line with the KYC/AML & CTF Policy.\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old or of legal age to form a binding contract under applicable law\n"
source_yaml_url: https://artifacts.apis.io/powertrade/eligibility/powertrade-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from PowerTrade's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- Derivatives
- Options
- Perpetual Futures
- Trading
- Exchange
- Financial Services
- WebSocket
- FIX
- Market Data
---
