---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are accepting these Terms and using the Services on behalf of a company, business, or organization, you represent and warrant that you are authorized to do so.
    type: business
  minimum_age:
    text: You are only permitted to use the Services if you are aged 18 or older.
    value: '18'
  restricted_uses:
  - summary: Prohibited business categories
    text: 'You may not use our Services in connection with any product, service, transaction or activity that: Not to reproduce, duplicate, copy or re-sell any part of our site in contravention of the provisions of our terms of website use.'
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: During the Trial Period, you will have limited access to our Platform and Services due to incomplete onboarding requirements and Know Your Customer (“KYC”) verification.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Duplo
provenance_date: '2026-11-09'
provider_name: Duplo
provider_slug: duplo
slug: duplo-eligibility
source_date: '2026-11-09'
source_filename: duplo-eligibility.yml
source_heading: Eligibility
source_page: https://tryduplo.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Duplo\naid: duplo\nurl: https://tryduplo.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are accepting these Terms and using the Services on behalf of a company, business, or organization,\n    you represent and warrant that you are authorized to do so.\nrestricted_uses:\n- summary: Prohibited business categories\n  text: 'You may not use our Services in connection with any product, service, transaction or activity that: Not\n    to reproduce, duplicate, copy or re-sell any part of our site in contravention\
  \ of the provisions of our terms\n    of website use.'\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: During the Trial Period, you will have limited access to our Platform and Services due to incomplete onboarding\n    requirements and Know Your Customer (“KYC”) verification.\nminimum_age:\n  value: '18'\n  text: You are only permitted to use the Services if you are aged 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/duplo/eligibility/duplo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Duplo's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Payments
- B2B Payments
- Cross-Border Payments
- Expense Management
- Virtual Accounts
- E-Invoicing
- Foreign Exchange
- Africa
- Nigeria
---
