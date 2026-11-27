---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - AF
    - BY
    - CU
    - IR
    - KP
    - RU
    - SY
    - VE
    served: []
    text: You are not located in, nor are you a citizen, resident, or agent of Afghanistan, Belarus, Cuba, Iran, North Korea, Russia (including Crimea, Donetsk, and Luhansk regions of Ukraine), Syria, or Venezuela (collectively, “Prohibited Jurisdictions”)
  minimum_age:
    text: You have reached the age of majority in your jurisdiction and possess the legal capacity to enter into binding contracts
    value: null
  restricted_uses:
  - summary: Sanctioned parties and Prohibited Jurisdictions
    text: You will not engage in transactions involving Prohibited Jurisdictions or sanctioned parties
  - summary: Circumventing restrictions
    text: Circumventing restrictions through VPNs, proxy servers, or similar tools is strictly forbidden and may result in legal consequences.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: Using the App requires creating an account with biometric verification to confirm you’re a unique person.
excluded_countries:
- AF
- BY
- CU
- IR
- KP
- RU
- SY
- VE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Alien
provenance_date: '2026-11-09'
provider_name: Alien
provider_slug: alien
slug: alien-eligibility
source_date: '2026-11-09'
source_filename: alien-eligibility.yml
source_heading: Eligibility
source_page: https://alien.org/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alien\naid: alien\nurl: https://alien.org/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - AF\n  - BY\n  - CU\n  - IR\n  - KP\n  - RU\n  - SY\n  - VE\n  text: You are not located in, nor are you a citizen, resident, or agent of Afghanistan, Belarus, Cuba, Iran, North\n    Korea, Russia (including Crimea, Donetsk, and Luhansk regions of Ukraine), Syria, or Venezuela (collectively,\n    “Prohibited Jurisdictions”)\nentity_types: []\nrestricted_uses:\n- summary: Sanctioned parties and Prohibited Jurisdictions\n  text: You will not engage in transactions involving Prohibited Jurisdictions\
  \ or sanctioned parties\n- summary: Circumventing restrictions\n  text: Circumventing restrictions through VPNs, proxy servers, or similar tools is strictly forbidden and may result\n    in legal consequences.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: Using the App requires creating an account with biometric verification to confirm you’re a unique person.\nminimum_age:\n  value: null\n  text: You have reached the age of majority in your jurisdiction and possess the legal capacity to enter into binding\n    contracts\n"
source_yaml_url: https://artifacts.apis.io/alien/eligibility/alien-eligibility.yml
stated_fields:
- countries
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Alien's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Identity
- Authentication
- OAuth
- OpenID Connect
- Proof of Humanity
- Blockchain
- Solana
- Agents
---
