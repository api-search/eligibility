---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    - CA
    - IR
    - CU
    - KP
    - SY
    - MM
    served: []
    text: MULTIPLI IS NOT OFFERED TO PERSONS OR ENTITIES WHO RESIDE IN, ARE CITIZENS OF, ARE LOCATED IN, ARE INCORPORATED IN, OR HAVE A REGISTERED OFFICE IN THE UNITED STATES OF AMERICA OR CANADA
  entity_types:
  - text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in which you reside and you have the legal capacity to enter into these Terms
    type: individual
  minimum_age:
    text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in which you reside
    value: null
  restricted_uses:
  - summary: Use from restricted territories or by sanctioned persons
    text: you must not be a resident, citizen or agent of, or incorporated in, and do not have a registered office in Iran, Cuba, North Korea, Syria, Myanmar (Burma), the regions of Crimea, Donetsk or Luhansk
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
- CA
- IR
- CU
- KP
- SY
- MM
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Multipli
provenance_date: '2026-11-10'
provider_name: Multipli
provider_slug: multipli
slug: multipli-eligibility
source_date: '2026-11-10'
source_filename: multipli-eligibility.yml
source_heading: Eligibility
source_page: https://docs.multipli.fi/legal/standard-website-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Multipli\naid: multipli\nurl: https://docs.multipli.fi/legal/standard-website-terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - CA\n  - IR\n  - CU\n  - KP\n  - SY\n  - MM\n  text: MULTIPLI IS NOT OFFERED TO PERSONS OR ENTITIES WHO RESIDE IN, ARE CITIZENS OF, ARE LOCATED IN, ARE INCORPORATED\n    IN, OR HAVE A REGISTERED OFFICE IN THE UNITED STATES OF AMERICA OR CANADA\nentity_types:\n- type: individual\n  text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in\n    which you reside and you have the legal capacity to\
  \ enter into these Terms\nrestricted_uses:\n- summary: Use from restricted territories or by sanctioned persons\n  text: you must not be a resident, citizen or agent of, or incorporated in, and do not have a registered office\n    in Iran, Cuba, North Korea, Syria, Myanmar (Burma), the regions of Crimea, Donetsk or Luhansk\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: if you are entering into these Terms as an individual, then you are of legal age in the jurisdiction in\n    which you reside\n"
source_yaml_url: https://artifacts.apis.io/multipli/eligibility/multipli-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Multipli's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Cryptocurrency
- DeFi
- Stablecoins
- Yield
- Real World Assets
- Tokenization
- Blockchain
- EVM
- Web3
---
