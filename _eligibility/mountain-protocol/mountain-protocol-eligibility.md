---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - US
    - CN
    - RU
    - IR
    - KP
    - CU
    - SY
    served: []
    text: Both your institution and the ultimate beneficial owners must be located in one or more of the jurisdictions supported by Mountain Protocol. Restricted jurisdictions include Afghanistan, Albania, ... China, ... Russian Federation, ... United States, ... Venezuela, ... Zimbabwe.
  entity_types:
  - text: Only institutions are eligible to create an account with Mountain Protocol. Individual accounts are not supported.
    type: business
  minimum_age:
    text: The representative opening the account must be at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: Illegal activity
    text: The institution and its representative/s agree that the Mountain Protocol account and USDM token will not be used for any illegal activity, including but not limited to, illegal gambling, money laundering, fraud, blackmail, extortion, ransoming data, terrorism financing, other violent activities, or any prohibited market practices.
  - summary: U.S. Persons
    text: Mountain Protocol restricts U.S. Persons' access to and usage of its Services, including but not limited to the USDM token.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: All accounts are subject to review and approval.
excluded_countries:
- US
- CN
- RU
- IR
- KP
- CU
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mountain Protocol
provenance_date: '2026-11-10'
provider_name: Mountain Protocol
provider_slug: mountain-protocol
slug: mountain-protocol-eligibility
source_date: '2026-11-10'
source_filename: mountain-protocol-eligibility.yml
source_heading: Eligibility
source_page: https://docs.mountainprotocol.com/legacy-legal-docs/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mountain Protocol\naid: mountain-protocol\nurl: https://docs.mountainprotocol.com/legacy-legal-docs/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - CN\n  - RU\n  - IR\n  - KP\n  - CU\n  - SY\n  text: Both your institution and the ultimate beneficial owners must be located in one or more of the jurisdictions\n    supported by Mountain Protocol. Restricted jurisdictions include Afghanistan, Albania, ... China, ... Russian\n    Federation, ... United States, ... Venezuela, ... Zimbabwe.\nentity_types:\n- type: business\n  text: Only institutions are eligible to\
  \ create an account with Mountain Protocol. Individual accounts are not\n    supported.\nrestricted_uses:\n- summary: Illegal activity\n  text: The institution and its representative/s agree that the Mountain Protocol account and USDM token will not\n    be used for any illegal activity, including but not limited to, illegal gambling, money laundering, fraud, blackmail,\n    extortion, ransoming data, terrorism financing, other violent activities, or any prohibited market practices.\n- summary: U.S. Persons\n  text: Mountain Protocol restricts U.S. Persons' access to and usage of its Services, including but not limited\n    to the USDM token.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: All accounts are subject to review and approval.\nminimum_age:\n  value: '18'\n  text: The representative opening the account must be at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/mountain-protocol/eligibility/mountain-protocol-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Mountain Protocol's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Web3
- Stablecoins
- DeFi
- Digital Assets
- Blockchain
- Ethereum
- Financial Services
- Yield
- Stablecoin Issuance
- Cryptocurrency
---
