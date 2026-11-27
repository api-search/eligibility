---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not all of the Services described on this Website are available in all geographic areas. We make no representation that the Website is appropriate or available for use beyond the United States of America.
  entity_types:
  - text: you are over the age of 18 (or older if you reside in a state where the majority age is older)
    type: individual
  - text: ON BEHALF OF A COMPANY AS AN AUTHORIZED REPRESENTATIVE OF THAT COMPANY. IF YOU ARE CONSENTING ON BEHALF OF A COMPANY, THEN YOU FURTHER REPRESENT TO US THAT YOU HAVE THE AUTHORITY TO BIND THE COMPANY
    type: business
  minimum_age:
    text: We do not knowingly market the Website or any Services to minors under eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Sanctioned countries and prohibited parties
    text: 'The Service is subject to U.S. export controls and may not be downloaded, exported, or re-exported: (i) into (or to a national or resident of) Burma (Myanmar), Cuba, Iran, North Korea, Sudan, Syria, Libya, or any other country with respect to which the U.S. government maintains trade sanctions'
  - summary: Illegal use
    text: Use the Service for any illegal purpose or in violation of any local, state, national, or international law;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hamsa
provenance_date: '2026-11-09'
provider_name: Hamsa
provider_slug: hamsa
slug: hamsa-eligibility
source_date: '2026-11-09'
source_filename: hamsa-eligibility.yml
source_heading: Eligibility
source_page: https://www.hamsa.com/legal/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hamsa\naid: hamsa\nurl: https://www.hamsa.com/legal/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Not all of the Services described on this Website are available in all geographic areas. We make no representation\n    that the Website is appropriate or available for use beyond the United States of America.\nentity_types:\n- type: individual\n  text: you are over the age of 18 (or older if you reside in a state where the majority age is older)\n- type: business\n  text: ON BEHALF OF A COMPANY AS AN AUTHORIZED REPRESENTATIVE OF THAT COMPANY. IF YOU ARE CONSENTING ON\
  \ BEHALF\n    OF A COMPANY, THEN YOU FURTHER REPRESENT TO US THAT YOU HAVE THE AUTHORITY TO BIND THE COMPANY\nrestricted_uses:\n- summary: Sanctioned countries and prohibited parties\n  text: 'The Service is subject to U.S. export controls and may not be downloaded, exported, or re-exported: (i)\n    into (or to a national or resident of) Burma (Myanmar), Cuba, Iran, North Korea, Sudan, Syria, Libya, or any\n    other country with respect to which the U.S. government maintains trade sanctions'\n- summary: Illegal use\n  text: Use the Service for any illegal purpose or in violation of any local, state, national, or international\n    law;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: We do not knowingly market the Website or any Services to minors under eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/hamsa/eligibility/hamsa-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Hamsa's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Financial Services
- Blockchain
- Payments
- Tokenization
- Privacy
- Zero-Knowledge Proofs
- CBDC
- Settlement
- DeFi
- EVM
- JSON-RPC
---
