---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - IR
    - KP
    - CU
    - SY
    - CN
    - AF
    - CF
    - CD
    - LY
    - ML
    - RU
    - SO
    - SD
    - YE
    served: []
    text: you shall not use QT if you or any of the authorized users ... are ... A citizen, domiciled in, resident of, or physically present / located in a U.S. sanctioned jurisdiction, including, but not limited to, Iran, North Korea, Cuba, Syria, China, Afghanistan, Central African Republic (the), Congo (the Democratic Republic of the), Libya, Mali, Russia, the Crimea region of Ukraine, Somalia, Sudan, or Yemen
  entity_types:
  - text: 'An entity: (A) which is incorporated in, or operates out of, an Excluded Jurisdiction'
    type: business
  minimum_age:
    text: you represent and warrant that you are of legal age to form a binding contract with us
    value: null
  restricted_uses:
  - summary: Military and critical infrastructure use
    text: Use QT in connection with military, defense, or critical infrastructure systems without our prior written consent or in violation of applicable law;
  - summary: Sanctioned persons
    text: 'An individual or entity: (A) included in the consolidated list published by the United Nations Security Council'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- IR
- KP
- CU
- SY
- CN
- AF
- CF
- CD
- LY
- ML
- RU
- SO
- SD
- YE
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Via Science
provenance_date: '2026-11-10'
provider_name: Via Science
provider_slug: via-science
slug: via-science-eligibility
source_date: '2026-11-10'
source_filename: via-science-eligibility.yml
source_heading: Eligibility
source_page: https://www.solvewithvia.com/qt-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Via Science\naid: via-science\nurl: https://www.solvewithvia.com/qt-terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - IR\n  - KP\n  - CU\n  - SY\n  - CN\n  - AF\n  - CF\n  - CD\n  - LY\n  - ML\n  - RU\n  - SO\n  - SD\n  - YE\n  text: you shall not use QT if you or any of the authorized users ... are ... A citizen, domiciled in, resident\n    of, or physically present / located in a U.S. sanctioned jurisdiction, including, but not limited to, Iran,\n    North Korea, Cuba, Syria, China, Afghanistan, Central African Republic (the), Congo (the Democratic Republic\n    of the),\
  \ Libya, Mali, Russia, the Crimea region of Ukraine, Somalia, Sudan, or Yemen\nentity_types:\n- type: business\n  text: 'An entity: (A) which is incorporated in, or operates out of, an Excluded Jurisdiction'\nrestricted_uses:\n- summary: Military and critical infrastructure use\n  text: Use QT in connection with military, defense, or critical infrastructure systems without our prior written\n    consent or in violation of applicable law;\n- summary: Sanctioned persons\n  text: 'An individual or entity: (A) included in the consolidated list published by the United Nations Security\n    Council'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: you represent and warrant that you are of legal age to form a binding contract with us\n"
source_yaml_url: https://artifacts.apis.io/via-science/eligibility/via-science-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Via Science's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Security
- Identity
- Authentication
- Zero Trust
- Decentralized Identity
- Verifiable Credentials
- Post-Quantum Cryptography
- Encryption
- File Transfer
- Defense
- Artificial Intelligence
- Blockchain
- OpenID Connect
---
