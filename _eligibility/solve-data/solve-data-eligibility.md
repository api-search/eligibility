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
    text: as of the Effective Date, Cuba, Iran, North Korea, Sudan, and Syria
  entity_types:
  - text: the customer listed on the applicable Order or SoW (“Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Excluded Data
    text: Customer warrants that (a) it has not and will not transmit Excluded Data
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
name: Solve Data
provenance_date: '2026-11-10'
provider_name: Solve Data
provider_slug: solve-data
slug: solve-data-eligibility
source_date: '2026-11-10'
source_filename: solve-data-eligibility.yml
source_heading: Eligibility
source_page: https://www.solve.io/legal-terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Solve Data\naid: solve-data\nurl: https://www.solve.io/legal-terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: as of the Effective Date, Cuba, Iran, North Korea, Sudan, and Syria\nentity_types:\n- type: business\n  text: the customer listed on the applicable Order or SoW (“Customer”)\nrestricted_uses:\n- summary: Excluded Data\n  text: Customer warrants that (a) it has not and will not transmit Excluded Data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value:\
  \ null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/solve-data/eligibility/solve-data-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Solve Data's own page on 2026-11-10.
synthetic: false
tags:
- Marketing Automation
- Software-as-a-Service
- Email Marketing
- Customer Engagement
- Content Creation
---
