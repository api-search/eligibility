---
api_specs:
- filename: postman.yaml
  format: yaml
  label: Klutch Public API
  slug: klutch-public-api
  spec_type: Postman
  url: https://api-docs.klutchcard.com/
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You are a resident of the United States with a United States mailing address;
  entity_types:
  - text: You must be at least eighteen (18) years old to use the Services.
    type: individual
  - text: A business cannot register for services through Klutch.
    type: business
  minimum_age:
    text: You must be at least eighteen (18) years old to use the Services.
    value: '18'
  restricted_uses:
  - summary: Business, commercial or resale use of cards
    text: Use any Klutch Card for business, commercial, or resale purposes.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: To help the government fight the funding of terrorism and money laundering activities, federal law requires all financial institutions to obtain, verify and record information identifying each person who opens a Klutch Account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Klutch
provenance_date: '2026-11-09'
provider_name: Klutch
provider_slug: klutch
slug: klutch-eligibility
source_date: '2026-11-09'
source_filename: klutch-eligibility.yml
source_heading: Eligibility
source_page: https://www.klutchcard.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Klutch\naid: klutch\nurl: https://www.klutchcard.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You are a resident of the United States with a United States mailing address;\nentity_types:\n- type: individual\n  text: You must be at least eighteen (18) years old to use the Services.\n- type: business\n  text: A business cannot register for services through Klutch.\nrestricted_uses:\n- summary: Business, commercial or resale use of cards\n  text: Use any Klutch Card for business, commercial, or resale purposes.\nverification:\n  kyc: true\n\
  \  kyb: null\n  approval_required: true\n  text: To help the government fight the funding of terrorism and money laundering activities, federal law requires\n    all financial institutions to obtain, verify and record information identifying each person who opens a Klutch\n    Account.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen (18) years old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/klutch/eligibility/klutch-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Klutch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Credit Cards
- Payments
- Card Issuing
- Virtual Cards
- Transaction
- Spend Management
- Personal Finance
- GraphQL
- Embedded Finance
- Agents
---
