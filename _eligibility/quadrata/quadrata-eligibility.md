---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - UA
    served: []
    text: 'The Services are operated within the United States. Export restrictions: Cuba, Iran, North Korea, Syria, Ukraine, or any other country with respect to which the United States maintains trade sanctions'
  entity_types:
  - text: you are at least eighteen (18) years of age or older (for U.S. based-Authorized Users)
    type: individual
  - text: If you are using the Services on behalf of a business or entity, you represent to us that you have the authority to bind that business or entity to these Terms
    type: business
  minimum_age:
    text: you are at least eighteen (18) years of age or older (for U.S. based-Authorized Users)
    value: '18'
  restricted_uses:
  - summary: Illegal activity
    text: You agree to comply with applicable law and to not use Services for any transaction or activity that is illegal
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- UA
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Quadrata
provenance_date: '2026-11-10'
provider_name: Quadrata
provider_slug: quadrata
slug: quadrata-eligibility
source_date: '2026-11-10'
source_filename: quadrata-eligibility.yml
source_heading: Eligibility
source_page: https://quadrata.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Quadrata\naid: quadrata\nurl: https://quadrata.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - UA\n  text: 'The Services are operated within the United States. Export restrictions: Cuba, Iran, North Korea, Syria,\n    Ukraine, or any other country with respect to which the United States maintains trade sanctions'\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years of age or older (for U.S. based-Authorized Users)\n- type: business\n  text: If you are using the Services on behalf of a business or entity,\
  \ you represent to us that you have the authority\n    to bind that business or entity to these Terms\nrestricted_uses:\n- summary: Illegal activity\n  text: You agree to comply with applicable law and to not use Services for any transaction or activity that is\n    illegal\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age or older (for U.S. based-Authorized Users)\n"
source_yaml_url: https://artifacts.apis.io/quadrata/eligibility/quadrata-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Quadrata's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web3
- Identity
- Digital Identity
- KYC
- KYB
- AML
- Compliance
- Wallet Screening
- Blockchain
- Decentralized Identity
---
