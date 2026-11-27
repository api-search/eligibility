---
claim_count: 3
description: ''
doc:
  countries:
    excluded:
    - AF
    - BY
    - CF
    - CU
    - ER
    - IR
    - IQ
    - LB
    - LY
    - CN
    - MM
    - KP
    - SO
    - SY
    - SD
    served: []
    text: 'you must... not be on a sanctions or restricted or prohibited list, or physically located in a country on such a list, of the United States of America, the European Union or any of its member states, or the United Kingdom including but not limited to the following countries or territories: Afghanistan, Belarus, Central African Republic, Crimea, Cuba, Eritrea, Iran, Iraq, Lebanon, Libya, Mainland China, Myanmar, North Korea,, Somalia, Syria, Sudan, the Donetsk and Luhansk regions of Ukraine.'
  minimum_age:
    text: you must be (i) at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Money laundering and sanctions evasion
    text: The Services shall not be used in connection with money laundering, financing illicit activities, Sanctions evasion or any other unlawful purposes.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- AF
- BY
- CF
- CU
- ER
- IR
- IQ
- LB
- LY
- CN
- MM
- KP
- SO
- SY
- SD
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: io.net
provenance_date: '2026-11-09'
provider_name: io.net
provider_slug: io-net
slug: io-net-eligibility
source_date: '2026-11-09'
source_filename: io-net-eligibility.yml
source_heading: Eligibility
source_page: https://io.net/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: io.net\naid: io-net\nurl: https://io.net/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - AF\n  - BY\n  - CF\n  - CU\n  - ER\n  - IR\n  - IQ\n  - LB\n  - LY\n  - CN\n  - MM\n  - KP\n  - SO\n  - SY\n  - SD\n  text: 'you must... not be on a sanctions or restricted or prohibited list, or physically located in a country\n    on such a list, of the United States of America, the European Union or any of its member states, or the United\n    Kingdom including but not limited to the following countries or territories: Afghanistan, Belarus, Central African\n    Republic, Crimea, Cuba, Eritrea,\
  \ Iran, Iraq, Lebanon, Libya, Mainland China, Myanmar, North Korea,, Somalia,\n    Syria, Sudan, the Donetsk and Luhansk regions of Ukraine.'\nentity_types: []\nrestricted_uses:\n- summary: Money laundering and sanctions evasion\n  text: The Services shall not be used in connection with money laundering, financing illicit activities, Sanctions\n    evasion or any other unlawful purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be (i) at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/io-net/eligibility/io-net-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from io.net's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- GPU
- Decentralized Compute
- DePIN
- Web3
- Solana
- Inference
- LLM
- Distributed Computing
- Ray
- Kubernetes
- Containers
- Confidential Compute
- Agents
- MCP
---
