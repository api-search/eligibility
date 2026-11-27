---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - EG
    text: The Service is available to customers having at least [18] years old and residing in Egypt.
  entity_types:
  - text: whether they are individuals, civil associations, or civil associations to which the contract has been contracted.
    type: individual
  minimum_age:
    text: The Service is available to customers having at least [18] years old and residing in Egypt.
    value: '18'
  restricted_uses:
  - summary: Personal non-commercial use only
    text: These Website Terms and Conditions permit you to use the Website for your personal, non-commercial use only.
  - summary: Egyptian nationality and single phone account
    text: Users should only be of Egyptian nationality.
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: Money Fellows may at its sole discretion, accept or reject, any demand received to participate in Money Fellows ROSCA without incurring any liabilities.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Moneyfellows
provenance_date: '2026-11-10'
provider_name: Moneyfellows
provider_slug: moneyfellows
slug: moneyfellows-eligibility
source_date: '2026-11-10'
source_filename: moneyfellows-eligibility.yml
source_heading: Eligibility
source_page: https://moneyfellows.com/en-us/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moneyfellows\naid: moneyfellows\nurl: https://moneyfellows.com/en-us/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - EG\n  excluded: []\n  text: The Service is available to customers having at least [18] years old and residing in Egypt.\nentity_types:\n- type: individual\n  text: whether they are individuals, civil associations, or civil associations to which the contract has been contracted.\nrestricted_uses:\n- summary: Personal non-commercial use only\n  text: These Website Terms and Conditions permit you to use the Website for your personal, non-commercial use only.\n- summary:\
  \ Egyptian nationality and single phone account\n  text: Users should only be of Egyptian nationality.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: Money Fellows may at its sole discretion, accept or reject, any demand received to participate in Money\n    Fellows ROSCA without incurring any liabilities.\nminimum_age:\n  value: '18'\n  text: The Service is available to customers having at least [18] years old and residing in Egypt.\n"
source_yaml_url: https://artifacts.apis.io/moneyfellows/eligibility/moneyfellows-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Moneyfellows's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Fintech
- Savings
- ROSCA
- Egypt
- Personal Finance
- Prepaid Cards
- Mobile App
---
