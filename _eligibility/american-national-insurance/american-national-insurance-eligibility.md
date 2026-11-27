---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: operates in all 50 states
  entity_types:
  - text: The words “user,” “you,” and “your” refer to each person using the American National website.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Products not offered where not licensed
    text: The product and/or service descriptions, if any, provided on the American National website are not intended to constitute an offer to sell or a solicitation to buy any product or service in any jurisdiction in which we are not properly licensed.
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
name: American National Insurance
provenance_date: '2026-11-09'
provider_name: American National Insurance
provider_slug: american-national-insurance
slug: american-national-insurance-eligibility
source_date: '2026-11-09'
source_filename: american-national-insurance-eligibility.yml
source_heading: Eligibility
source_page: https://www.americannational.com/home/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: American National Insurance\naid: american-national-insurance\nurl: https://www.americannational.com/home/legal/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: operates in all 50 states\nentity_types:\n- type: individual\n  text: The words “user,” “you,” and “your” refer to each person using the American National website.\nrestricted_uses:\n- summary: Products not offered where not licensed\n  text: The product and/or service descriptions, if any, provided on the American National website are not intended\n    to constitute an offer to sell or a solicitation\
  \ to buy any product or service in any jurisdiction in which\n    we are not properly licensed.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/american-national-insurance/eligibility/american-national-insurance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from American National Insurance's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Life Insurance
- Annuities
- Health Insurance
- Property and Casualty
- Pensions
- Financial Services
- Fortune 1000
---
