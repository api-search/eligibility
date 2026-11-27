---
claim_count: 4
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
    text: Company agrees that (i) it is not, and is not acting on behalf of, any person who is a citizen, national, or resident of, or who is controlled by the government of, Cuba, Iran, North Korea, Sudan, or Syria
  entity_types:
  - text: “ You ” or “ Your ” means You, either individually, or in your capacity as an authorized representative for the Company you are binding to these Terms.
    type: individual
  - text: “ Company ” means the person or entity acquiring Services from Siepe.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Weapons and prohibited development
    text: it will not use the Services, Deliverables, and software for, and will not permit the Services, Deliverables, and software to be used for, any purposes prohibited by law, including, without limitation, for any prohibited development, design, manufacture or production of missiles or nuclear, chemical or biological weapons.
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
name: Siepe
provenance_date: '2026-11-10'
provider_name: Siepe
provider_slug: siepe
slug: siepe-eligibility
source_date: '2026-11-10'
source_filename: siepe-eligibility.yml
source_heading: Eligibility
source_page: https://www.siepe.com/terms-of-use-2022-1/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Siepe\naid: siepe\nurl: https://www.siepe.com/terms-of-use-2022-1/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SD\n  - SY\n  text: Company agrees that (i) it is not, and is not acting on behalf of, any person who is a citizen, national,\n    or resident of, or who is controlled by the government of, Cuba, Iran, North Korea, Sudan, or Syria\nentity_types:\n- type: individual\n  text: “ You ” or “ Your ” means You, either individually, or in your capacity as an authorized representative\n    for the Company you are binding to these Terms.\n- type: business\n  text:\
  \ “ Company ” means the person or entity acquiring Services from Siepe.\nrestricted_uses:\n- summary: Weapons and prohibited development\n  text: it will not use the Services, Deliverables, and software for, and will not permit the Services, Deliverables,\n    and software to be used for, any purposes prohibited by law, including, without limitation, for any prohibited\n    development, design, manufacture or production of missiles or nuclear, chemical or biological weapons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/siepe/eligibility/siepe-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Siepe's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- Private Credit
- CLO
- Alternative Investments
- Portfolio Management
- Data Management
- Fund Administration
- Middle Office
- Managed Service
- Fintech
---
