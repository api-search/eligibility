---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: you are located in the United States
  minimum_age:
    text: you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: you shall not use the Services in any way that may constitute a violation of any applicable law, regulation, rule or ordinance
  - summary: Fraudulent use or interference
    text: you will not use the Services, directly or indirectly, for any fraudulent undertaking or in any manner so as to interfere with the operation of the Services
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
name: MANTL
provenance_date: '2026-11-10'
provider_name: MANTL
provider_slug: mantl
slug: mantl-eligibility
source_date: '2026-11-10'
source_filename: mantl-eligibility.yml
source_heading: Eligibility
source_page: https://www.mantl.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: MANTL\naid: mantl\nurl: https://www.mantl.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: you are located in the United States\nentity_types: []\nrestricted_uses:\n- summary: Unlawful use\n  text: you shall not use the Services in any way that may constitute a violation of any applicable law, regulation,\n    rule or ordinance\n- summary: Fraudulent use or interference\n  text: you will not use the Services, directly or indirectly, for any fraudulent undertaking or in any manner so\n    as to interfere with the operation of the Services\nverification:\n  kyc:\
  \ null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/mantl/eligibility/mantl-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from MANTL's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Banking
- Credit Union
- Account Opening
- Deposit Origination
- Loan Origination
- Fintech
- Onboarding
---
