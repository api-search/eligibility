---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - KE
    text: Hello Kenya! Come check out our premium devices!
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: true
    kyb: null
    kyc: true
    text: 'In order for the Lender to assess the Loan application and to provide the Loan, the Borrower provides the Lender with certain personal information including but not limited to: name, address, telephone, date of birth, income details, copy of ID document'
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mophones
provenance_date: '2026-11-10'
provider_name: Mophones
provider_slug: mophones
slug: mophones-eligibility
source_date: '2026-11-10'
source_filename: mophones-eligibility.yml
source_heading: Eligibility
source_page: https://mophones.co/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mophones\naid: mophones\nurl: https://mophones.co/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - KE\n  excluded: []\n  text: Hello Kenya! Come check out our premium devices!\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: true\n  kyb: null\n  approval_required: true\n  text: 'In order for the Lender to assess the Loan application and to provide the Loan, the Borrower provides the\n    Lender with certain personal information including but not limited to: name, address, telephone, date of birth,\n    income details, copy of ID document'\nminimum_age:\n  value: null\n\
  \  text: null\n"
source_yaml_url: https://artifacts.apis.io/mophones/eligibility/mophones-eligibility.yml
stated_fields:
- countries
- verification
summary_line: 2 quoted statements, read from Mophones's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Commerce
- Agentic Commerce
- Universal Commerce Protocol
- MCP
- Shopify
- Fintech
- Recommerce
- Africa
---
