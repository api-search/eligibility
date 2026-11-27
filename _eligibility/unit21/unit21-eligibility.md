---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SD
    - SY
    served: []
    text: Customer shall not permit any third party to access or use the Services in, or export such software to, a country subject to a United States embargo (as of the Effective Date, Cuba, Iran, North Korea, Sudan, and Syria).
  entity_types:
  - text: the corporation, LLC, partnership, sole proprietorship, or other business entity executing this Agreement (“Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: FCRA consumer report restriction
    text: Customer is prohibited from using the Services or the Workbench, in whole or in part, for the purpose of serving as a factor in establishing a person’s eligibility for credit, insurance, employment, or another purpose in connection with which a consumer report may be used under the FCRA.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Unit21
provenance_date: '2026-11-10'
provider_name: Unit21
provider_slug: unit21
slug: unit21-eligibility
source_date: '2026-11-10'
source_filename: unit21-eligibility.yml
source_heading: Eligibility
source_page: https://www.unit21.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Unit21\naid: unit21\nurl: https://www.unit21.ai/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer shall not permit any third party to access or use the Services in, or export such software to,\n    a country subject to a United States embargo (as of the Effective Date, Cuba, Iran, North Korea, Sudan, and\n    Syria).\nentity_types:\n- type: business\n  text: the corporation, LLC, partnership, sole proprietorship, or other business entity executing this Agreement\n    (“Customer”)\nrestricted_uses:\n- summary: FCRA consumer report restriction\n\
  \  text: Customer is prohibited from using the Services or the Workbench, in whole or in part, for the purpose of\n    serving as a factor in establishing a person’s eligibility for credit, insurance, employment, or another purpose\n    in connection with which a consumer report may be used under the FCRA.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/unit21/eligibility/unit21-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Unit21's own page on 2026-11-10.
synthetic: false
tags:
- Fraud Prevention
- AML
- Compliance
- Fintech
- Transaction Monitoring
- Risk Management
- SAR
- Financial Crime
- Suspicious Activity Reports
---
