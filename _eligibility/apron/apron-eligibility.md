---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    text: is a resident in the UK
  entity_types:
  - text: 'an individual of at least 18 years of age who: is entering into this Agreement in relation to business activities; is a resident in the UK'
    type: individual
  - text: 'a legal entity that is: incorporated or established in the UK; has a principal place of business in the UK'
    type: business
  minimum_age:
    text: an individual of at least 18 years of age
    value: '18'
  restricted_uses:
  - summary: Restricted payment categories
    text: the prohibition of certain categories of payment transactions (for example, payments in relation to the gaming, bitcoins and virtual currencies sectors)
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
name: Apron
provenance_date: '2026-11-09'
provider_name: Apron
provider_slug: apron
slug: apron-eligibility
source_date: '2026-11-09'
source_filename: apron-eligibility.yml
source_heading: Eligibility
source_page: https://getapron.com/terms-and-policies/apron-payments
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Apron\naid: apron\nurl: https://getapron.com/terms-and-policies/apron-payments\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - GB\n  excluded: []\n  text: is a resident in the UK\nentity_types:\n- type: individual\n  text: 'an individual of at least 18 years of age who: is entering into this Agreement in relation to business\n    activities; is a resident in the UK'\n- type: business\n  text: 'a legal entity that is: incorporated or established in the UK; has a principal place of business in the\n    UK'\nrestricted_uses:\n- summary: Restricted payment categories\n  text: the prohibition\
  \ of certain categories of payment transactions (for example, payments in relation to the\n    gaming, bitcoins and virtual currencies sectors)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: an individual of at least 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/apron/eligibility/apron-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Apron's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- Accounts Payable
- Bill Pay
- Accounting
- Payroll
- Expenses
- Small Business
- Reconciliation
---
