---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THE AGREEMENT IS BETWEEN US AND YOU, AN INDIVIDUAL ACTING ON BEHALF OF A LEGAL ENTITY THAT WILL BE USING THE SERVICE ("Customer").
    type: business
  minimum_age:
    text: THAT YOU ARE OF LEGAL AGE AND CAPACITY TO FORM A BINDING CONTRACT
    value: null
  restricted_uses:
  - summary: Not financial advice
    text: CONTENT PROVIDED THROUGH THE SERVICE IS NOT INTENDED TO BE USED AS FINANCIAL OR INVESTMENT ADVICE
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Access to any part of the Service is available only to registered users.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cash Flow Frog
provenance_date: '2026-11-09'
provider_name: Cash Flow Frog
provider_slug: cashflowfrog-com
slug: cashflowfrog-com-eligibility
source_date: '2026-11-09'
source_filename: cashflowfrog-com-eligibility.yml
source_heading: Eligibility
source_page: https://cashflowfrog.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cash Flow Frog\naid: cashflowfrog-com\nurl: https://cashflowfrog.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: THE AGREEMENT IS BETWEEN US AND YOU, AN INDIVIDUAL ACTING ON BEHALF OF A LEGAL ENTITY THAT WILL BE USING\n    THE SERVICE (\"Customer\").\nrestricted_uses:\n- summary: Not financial advice\n  text: CONTENT PROVIDED THROUGH THE SERVICE IS NOT INTENDED TO BE USED AS FINANCIAL OR INVESTMENT ADVICE\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Access to any part of the Service\
  \ is available only to registered users.\nminimum_age:\n  value: null\n  text: THAT YOU ARE OF LEGAL AGE AND CAPACITY TO FORM A BINDING CONTRACT\n"
source_yaml_url: https://artifacts.apis.io/cashflowfrog-com/eligibility/cashflowfrog-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Cash Flow Frog's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Forecasting
- Software-as-a-Service
- Accounting
- Small Business
---
