---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - IA
    served: []
    text: 'Currently, loans are not offered in: IA.'
  entity_types:
  - text: Individual borrowers must be at least 18 years old and have a valid social security number and a valid checking account.
    type: individual
  minimum_age:
    text: Individual borrowers must be at least 18 years old and have a valid social security number and a valid checking account.
    value: '18'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All loans are subject to credit review and approval.
excluded_countries:
- IA
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Happy Money
provenance_date: '2026-11-09'
provider_name: Happy Money
provider_slug: happymoney
slug: happymoney-eligibility
source_date: '2026-11-09'
source_filename: happymoney-eligibility.yml
source_heading: Eligibility
source_page: https://happymoney.com/privacy-and-legal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Happy Money\naid: happymoney\nurl: https://happymoney.com/privacy-and-legal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IA\n  text: 'Currently, loans are not offered in: IA.'\nentity_types:\n- type: individual\n  text: Individual borrowers must be at least 18 years old and have a valid social security number and a valid checking\n    account.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All loans are subject to credit review and approval.\nminimum_age:\n  value: '18'\n  text: Individual borrowers must be at least 18 years old and\
  \ have a valid social security number and a valid checking\n    account.\n"
source_yaml_url: https://artifacts.apis.io/happymoney/eligibility/happymoney-eligibility.yml
stated_fields:
- countries
- entity_types
- verification
- minimum_age
summary_line: 4 quoted statements, read from Happy Money's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Lending
- Personal Loans
- Debt Consolidation
- Consumer Finance
- Credit Union
- Financial Services
---
