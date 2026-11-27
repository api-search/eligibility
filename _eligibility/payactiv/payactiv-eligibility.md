---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or abusive conduct
    text: You agree that you will use the Service in compliance with all applicable laws, rules and regulations.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register for and create an account with the Service in order to access certain information, products, services, and features offered through the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: PayActiv
provenance_date: '2026-11-10'
provider_name: PayActiv
provider_slug: payactiv
slug: payactiv-eligibility
source_date: '2026-11-10'
source_filename: payactiv-eligibility.yml
source_heading: Eligibility
source_page: https://payactiv.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PayActiv\naid: payactiv\nurl: https://payactiv.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or abusive conduct\n  text: You agree that you will use the Service in compliance with all applicable laws, rules and regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register for and create an account with the Service in order to access certain information,\n    products, services, and features offered through the Service.\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/payactiv/eligibility/payactiv-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from PayActiv's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Earned Wage Access
- Payments
- Payroll
- Human Resources
- Cards
- Financial Wellness
- Fintech
---
