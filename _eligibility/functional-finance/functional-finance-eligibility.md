---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: The Website is available to such persons residing in the United States who can form legally binding agreements under applicable law.
  entity_types:
  - text: The Services are designed to be used by insurance companies and their partners.
    type: business
  minimum_age:
    text: Any use or access by anyone under the age of 13 is not permitted.
    value: '13'
  restricted_uses:
  - summary: Business or commercial use of accounts
    text: You agree to use your Account only for business or commercial purposes.
  - summary: Card payments limited to insured parties
    text: You agree to access and use the Card Payment Services only to process payments from Insured Parties in accordance with Section 10.
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
name: Functional Finance
provenance_date: '2026-11-09'
provider_name: Functional Finance
provider_slug: functional-finance
slug: functional-finance-eligibility
source_date: '2026-11-09'
source_filename: functional-finance-eligibility.yml
source_heading: Eligibility
source_page: https://www.functionalfi.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Functional Finance\naid: functional-finance\nurl: https://www.functionalfi.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: The Website is available to such persons residing in the United States who can form legally binding agreements\n    under applicable law.\nentity_types:\n- type: business\n  text: The Services are designed to be used by insurance companies and their partners.\nrestricted_uses:\n- summary: Business or commercial use of accounts\n  text: You agree to use your Account only for business or commercial purposes.\n- summary:\
  \ Card payments limited to insured parties\n  text: You agree to access and use the Card Payment Services only to process payments from Insured Parties in accordance\n    with Section 10.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: Any use or access by anyone under the age of 13 is not permitted.\n"
source_yaml_url: https://artifacts.apis.io/functional-finance/eligibility/functional-finance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Functional Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Insurance
- Fintech
- Payments
- Billing
---
