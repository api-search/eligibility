---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - CU
    - IQ
    - LY
    - KP
    - IR
    - SD
    - SY
    served: []
    text: 'No software from the Site may be downloaded or exported: into (or to a national or resident of) Cuba, Iraq, Libya, North Korea, Iran, Sudan, Syria, or any other country to which the United States has embargoed goods'
  entity_types:
  - text: You will only use the Site or Services for a bona fide business purpose.
    type: business
  - text: You must be eighteen (18) years of age or older and capable of entering into legally binding contracts under applicable law to use the Site or Services.
    type: individual
  minimum_age:
    text: You must be eighteen (18) years of age or older
    value: '18'
  restricted_uses:
  - summary: No personal or household use
    text: You will not use the Site or Services for personal, family or household purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: When you open an account, we will ask for your name, address, date of birth, and other information that will allow us to identify you.
excluded_countries:
- CU
- IQ
- LY
- KP
- IR
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Provide
provenance_date: '2026-11-10'
provider_name: Provide
provider_slug: provide
slug: provide-eligibility
source_date: '2026-11-10'
source_filename: provide-eligibility.yml
source_heading: Eligibility
source_page: https://www.getprovide.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Provide\naid: provide\nurl: https://www.getprovide.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IQ\n  - LY\n  - KP\n  - IR\n  - SD\n  - SY\n  text: 'No software from the Site may be downloaded or exported: into (or to a national or resident of) Cuba, Iraq,\n    Libya, North Korea, Iran, Sudan, Syria, or any other country to which the United States has embargoed goods'\nentity_types:\n- type: business\n  text: You will only use the Site or Services for a bona fide business purpose.\n- type: individual\n  text: You must be eighteen (18) years of age or\
  \ older and capable of entering into legally binding contracts under\n    applicable law to use the Site or Services.\nrestricted_uses:\n- summary: No personal or household use\n  text: You will not use the Site or Services for personal, family or household purposes.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: When you open an account, we will ask for your name, address, date of birth, and other information that\n    will allow us to identify you.\nminimum_age:\n  value: '18'\n  text: You must be eighteen (18) years of age or older\n"
source_yaml_url: https://artifacts.apis.io/provide/eligibility/provide-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Provide's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Health Tech
- Fintech
- Banking
- Lending
- Financial Services
- Practice Finance
- SBA Loans
---
