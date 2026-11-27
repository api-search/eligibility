---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: (i) you in your individual capacity
    type: individual
  - text: (iii) you as the Company for which its Representatives use and/or access the Services or Platform
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful business purposes only
    text: Customer must use the Services only for lawful business purposes and in compliance with all applicable laws, including KYC, AML, sanctions, and tax obligations.
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
name: Oatfi
provenance_date: '2026-11-10'
provider_name: Oatfi
provider_slug: oatfi
slug: oatfi-eligibility
source_date: '2026-11-10'
source_filename: oatfi-eligibility.yml
source_heading: Eligibility
source_page: https://oatfi.com/platform-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Oatfi\naid: oatfi\nurl: https://oatfi.com/platform-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: (i) you in your individual capacity\n- type: business\n  text: (iii) you as the Company for which its Representatives use and/or access the Services or Platform\nrestricted_uses:\n- summary: Lawful business purposes only\n  text: Customer must use the Services only for lawful business purposes and in compliance with all applicable laws,\n    including KYC, AML, sanctions, and tax obligations.\nverification:\n  kyc: null\n\
  \  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/oatfi/eligibility/oatfi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Oatfi's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Embedded Finance
- B2B Payments
- Embedded Lending
- Working Capital
- Accounts Payable
- Accounts Receivable
- Commercial Cards
- Credit
---
