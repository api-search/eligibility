---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - EG
    text: The Service is available to customers having at least [18] years old and residing in Egypt.
  entity_types:
  - text: Users should only be of Egyptian nationality.
    type: individual
  minimum_age:
    text: The Service is available to customers having at least [18] years old and residing in Egypt.
    value: '18'
  restricted_uses:
  - summary: Personal use of website
    text: Given that the nature of the website is reserved for the ROSCA Customers, the use of the of such will be limited to the customers the only.
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
name: MFellows
provenance_date: '2026-11-10'
provider_name: MFellows
provider_slug: mfellows
slug: mfellows-eligibility
source_date: '2026-11-10'
source_filename: mfellows-eligibility.yml
source_heading: Eligibility
source_page: https://moneyfellows.com/en-us/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MFellows\naid: mfellows\nurl: https://moneyfellows.com/en-us/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EG\n  excluded: []\n  text: The Service is available to customers having at least [18] years old and residing in Egypt.\nentity_types:\n- type: individual\n  text: Users should only be of Egyptian nationality.\nrestricted_uses:\n- summary: Personal use of website\n  text: Given that the nature of the website is reserved for the ROSCA Customers, the use of the of such will be\n    limited to the customers the only.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Service is available to customers having at least [18] years old and residing in Egypt.\n"
source_yaml_url: https://artifacts.apis.io/mfellows/eligibility/mfellows-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MFellows's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Financial Services
- Savings
- Lending
- ROSCA
- Payments
- Egypt
- Mobile
- Consumer Finance
---
