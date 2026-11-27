---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: is a legal resident of the United States.
  entity_types:
  - text: The Qapital Service is offered and available to any user who is 18 years of age or older, has the legal capacity to form a binding contract with Qapital, and is a legal resident of the United States.
    type: individual
  minimum_age:
    text: 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Illegal purposes and money laundering
    text: Violate any Law or for any illegal purpose, including, without limitation, any Law governing theft, wire fraud, money laundering
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: We may at any time require you to provide additional information in order to verify your identity.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Qapital
provenance_date: '2026-11-10'
provider_name: Qapital
provider_slug: qapital
slug: qapital-eligibility
source_date: '2026-11-10'
source_filename: qapital-eligibility.yml
source_heading: Eligibility
source_page: https://www.qapital.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Qapital\naid: qapital\nurl: https://www.qapital.com/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: is a legal resident of the United States.\nentity_types:\n- type: individual\n  text: The Qapital Service is offered and available to any user who is 18 years of age or older, has the legal\n    capacity to form a binding contract with Qapital, and is a legal resident of the United States.\nrestricted_uses:\n- summary: Illegal purposes and money laundering\n  text: Violate any Law or for any illegal purpose, including, without limitation, any Law governing\
  \ theft, wire\n    fraud, money laundering\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: We may at any time require you to provide additional information in order to verify your identity.\nminimum_age:\n  value: '18'\n  text: 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/qapital/eligibility/qapital-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Qapital's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Personal Finance
- Savings
- Banking
- Investing
- Budgeting
- Fintech
- Consumer Applications
- Behavioral Economics
- Mobile Banking
---
