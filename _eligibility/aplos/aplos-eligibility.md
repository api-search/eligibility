---
claim_count: 6
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
    text: Customer shall not permit any third party to access or use the System in, or export such software to, a country subject to a United States embargo (as of the Effective Date, Cuba, Iran, North Korea, Sudan, and Syria).
  entity_types:
  - text: non-profit or other business entity executing this Agreement ("Customer")
    type: business
  - text: the sole proprietorship of an individual 18 years or older, or another entity authorized to do business pursuant to applicable law
    type: individual
  minimum_age:
    text: the sole proprietorship of an individual 18 years or older
    value: '18'
  restricted_uses:
  - summary: Excluded regulated data
    text: HITECH/HIPAA, COPPA, FINRA, CAN-SPAM
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: In order to process Online Payments, Organizations must be approved, which Aplos may, at its own discretion, approve or deny based on its underwriting requirements
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
name: Aplos
provenance_date: '2026-11-09'
provider_name: Aplos
provider_slug: aplos
slug: aplos-eligibility
source_date: '2026-11-09'
source_filename: aplos-eligibility.yml
source_heading: Eligibility
source_page: https://www.aplos.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aplos\naid: aplos\nurl: https://www.aplos.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Customer shall not permit any third party to access or use the System in, or export such software to, a\n    country subject to a United States embargo (as of the Effective Date, Cuba, Iran, North Korea, Sudan, and Syria).\nentity_types:\n- type: business\n  text: non-profit or other business entity executing this Agreement (\"Customer\")\n- type: individual\n  text: the sole proprietorship of an individual 18 years or older, or another entity authorized\
  \ to do business\n    pursuant to applicable law\nrestricted_uses:\n- summary: Excluded regulated data\n  text: HITECH/HIPAA, COPPA, FINRA, CAN-SPAM\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: In order to process Online Payments, Organizations must be approved, which Aplos may, at its own discretion,\n    approve or deny based on its underwriting requirements\nminimum_age:\n  value: '18'\n  text: the sole proprietorship of an individual 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/aplos/eligibility/aplos-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Aplos's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Accounting
- Non-Profit
- Software
- Cloud
---
