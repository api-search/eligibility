---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - US
    served:
    - GB
    text: You must be a UK resident, for UK tax purposes, to use our Products and Services. You must not be a US citizen, resident or a green card holder and not subject to US taxation.
  entity_types:
  - text: You must be over 18 years old to use our Products and Services and maintain an individual bank account that is personal to you and not used for business or commercial purposes.
    type: individual
  - text: Plum does not accept banking accounts which are held by legal entities.
    type: business
  minimum_age:
    text: You must be over 18 years old to use our Products and Services
    value: '18'
  restricted_uses:
  - summary: Domestic and private use only
    text: you will do so for domestic and private purposes only and you will not use any of the Products and Services for any commercial, business or resale purposes
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Plum
provenance_date: '2026-11-10'
provider_name: Plum
provider_slug: plum
slug: plum-eligibility
source_date: '2026-11-10'
source_filename: plum-eligibility.yml
source_heading: Eligibility
source_page: https://withplum.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Plum\naid: plum\nurl: https://withplum.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded:\n  - US\n  text: You must be a UK resident, for UK tax purposes, to use our Products and Services. You must not be a US citizen,\n    resident or a green card holder and not subject to US taxation.\nentity_types:\n- type: individual\n  text: You must be over 18 years old to use our Products and Services and maintain an individual bank account that\n    is personal to you and not used for business or commercial purposes.\n- type: business\n  text: Plum does not accept\
  \ banking accounts which are held by legal entities.\nrestricted_uses:\n- summary: Domestic and private use only\n  text: you will do so for domestic and private purposes only and you will not use any of the Products and Services\n    for any commercial, business or resale purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be over 18 years old to use our Products and Services\n"
source_yaml_url: https://artifacts.apis.io/plum/eligibility/plum-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Plum's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Personal Finance
- Savings
- Investing
- Wealth Management
- Consumer
- Mobile App
---
