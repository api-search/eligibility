---
claim_count: 6
description: ''
doc:
  countries:
    excluded:
    - IR
    - KP
    - SD
    - SS
    - SY
    - CU
    - RU
    served: []
    text: The Services are not available where prohibited by law or by Ramp Network policy, as updated from time to time; currently, such places include, but are not necessarily limited to, the countries of Iran, North Korea, Sudan, South Sudan, Syria, Cuba, Russia
  entity_types:
  - text: 'You can only sign-up for and use the Services if you: are at least 18 years old'
    type: individual
  minimum_age:
    text: are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No gambling
    text: you will not access or use the Services to engage in activities relating to gambling, betting or similar games of chance
  - summary: No regulated securities or derivatives
    text: use the Services to purchase or sell Digital Assets that are regulated securities, derivatives or financial instruments
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: satisfy all of our due diligence, “know-your-customer” and anti-money laundering requirements
excluded_countries:
- IR
- KP
- SD
- SS
- SY
- CU
- RU
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Ramp Network
provenance_date: '2026-11-10'
provider_name: Ramp Network
provider_slug: ramp-network
slug: ramp-network-eligibility
source_date: '2026-11-10'
source_filename: ramp-network-eligibility.yml
source_heading: Eligibility
source_page: https://rampnetwork.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ramp Network\naid: ramp-network\nurl: https://rampnetwork.com/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded:\n  - IR\n  - KP\n  - SD\n  - SS\n  - SY\n  - CU\n  - RU\n  text: The Services are not available where prohibited by law or by Ramp Network policy, as updated from time to\n    time; currently, such places include, but are not necessarily limited to, the countries of Iran, North Korea,\n    Sudan, South Sudan, Syria, Cuba, Russia\nentity_types:\n- type: individual\n  text: 'You can only sign-up for and use the Services if you: are at least 18 years\
  \ old'\nrestricted_uses:\n- summary: No gambling\n  text: you will not access or use the Services to engage in activities relating to gambling, betting or similar\n    games of chance\n- summary: No regulated securities or derivatives\n  text: use the Services to purchase or sell Digital Assets that are regulated securities, derivatives or financial\n    instruments\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: satisfy all of our due diligence, “know-your-customer” and anti-money laundering requirements\nminimum_age:\n  value: '18'\n  text: are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/ramp-network/eligibility/ramp-network-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 6 quoted statements, read from Ramp Network's own page on 2026-11-10.
synthetic: false
tags:
- Cryptocurrency
- Payments
- Fintech
- On-Ramp
- Off-Ramp
- Blockchain
- Web3
- Wallets
- Digital Assets
- Compliance
- Embedded Finance
---
