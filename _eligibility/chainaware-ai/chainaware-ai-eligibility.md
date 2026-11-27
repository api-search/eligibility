---
api_specs:
- filename: chainaware-ai-behaviour-prediction-api-api-openapi.yml
  format: yaml
  label: ChainAware.ai Behaviour Prediction API
  slug: chainaware-ai-behaviour-prediction-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainaware-ai/openapi/chainaware-ai-behaviour-prediction-api-api-openapi.yml
- filename: chainaware-ai-credit-score-api-api-openapi.yml
  format: yaml
  label: ChainAware.ai Credit Score API
  slug: chainaware-ai-credit-score-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainaware-ai/openapi/chainaware-ai-credit-score-api-api-openapi.yml
- filename: chainaware-ai-fraud-api-api-openapi.yml
  format: yaml
  label: ChainAware.ai Fraud API
  slug: chainaware-ai-fraud-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/chainaware-ai/openapi/chainaware-ai-fraud-api-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    - BY
    served: []
    text: 'You are not permitted to access the Platform if you are a citizen or resident of, or physically located in, any of the following jurisdictions: Cuba, Iran, Democratic People’s Republic of Korea (North Korea), Syria, the Crimea, Donetsk, and Luhansk regions of Ukraine, or the Russian Federation and Belarus'
  entity_types:
  - text: By accessing or using the Platform, you represent and warrant that you are at least 18 years of age, or the age of legal majority in your jurisdiction of residence if higher
    type: individual
  - text: Business Client registers by connecting a wallet, selecting an Enterprise Account, and providing accurate business identification details, including company name, registered address, and relevant contact information
    type: business
  minimum_age:
    text: you are at least 18 years of age, or the age of legal majority in your jurisdiction of residence if higher
    value: '18'
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
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: ChainAware.ai
provenance_date: '2026-11-09'
provider_name: ChainAware.ai
provider_slug: chainaware-ai
slug: chainaware-ai-eligibility
source_date: '2026-11-09'
source_filename: chainaware-ai-eligibility.yml
source_heading: Eligibility
source_page: https://chainaware.ai/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ChainAware.ai\naid: chainaware-ai\nurl: https://chainaware.ai/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  - BY\n  text: 'You are not permitted to access the Platform if you are a citizen or resident of, or physically located\n    in, any of the following jurisdictions: Cuba, Iran, Democratic People’s Republic of Korea (North Korea), Syria,\n    the Crimea, Donetsk, and Luhansk regions of Ukraine, or the Russian Federation and Belarus'\nentity_types:\n- type: individual\n  text: By accessing or using the Platform, you represent and warrant\
  \ that you are at least 18 years of age, or\n    the age of legal majority in your jurisdiction of residence if higher\n- type: business\n  text: Business Client registers by connecting a wallet, selecting an Enterprise Account, and providing accurate\n    business identification details, including company name, registered address, and relevant contact information\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age, or the age of legal majority in your jurisdiction of residence if higher\n"
source_yaml_url: https://artifacts.apis.io/chainaware-ai/eligibility/chainaware-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 4 quoted statements, read from ChainAware.ai's own page on 2026-11-09.
synthetic: false
tags:
- Blockchain
- Web3
- DeFi
- Fraud Prevention
- AML
- Compliance
- Credit Scoring
- Risk Scoring
- Smart Contract Security
- Agent Trust
- MCP
- A2A
- x402
- Agents
- Agent-Native
- Estonia
---
