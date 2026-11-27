---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are a legal, permanent resident of a country other than the United States
  entity_types:
  - text: This is a legal agreement between Higlobe and you or the company through which you are doing business
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Defense sector customers
    text: Customers engaged in the defense sector or the manufacture or production of arms, military equipment or weapons of mass destruction.
  - summary: Personal (non-commercial) use
    text: Receive or make a payment or transfer for a personal (non-commercial) purpose
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
name: Higlobe
provenance_date: '2026-11-09'
provider_name: Higlobe
provider_slug: higlobe
slug: higlobe-eligibility
source_date: '2026-11-09'
source_filename: higlobe-eligibility.yml
source_heading: Eligibility
source_page: https://higlobe.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Higlobe\naid: higlobe\nurl: https://higlobe.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: you are a legal, permanent resident of a country other than the United States\nentity_types:\n- type: business\n  text: This is a legal agreement between Higlobe and you or the company through which you are doing business\nrestricted_uses:\n- summary: Defense sector customers\n  text: Customers engaged in the defense sector or the manufacture or production of arms, military equipment or\n    weapons of mass destruction.\n- summary: Personal (non-commercial)\
  \ use\n  text: Receive or make a payment or transfer for a personal (non-commercial) purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/higlobe/eligibility/higlobe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Higlobe's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Payments
- Cross-Border Payments
- Money Transfer
- Remittances
- Fintech
- Financial Services
- Freelancers
- Receiving Accounts
---
