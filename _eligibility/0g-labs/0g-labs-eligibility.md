---
api_specs:
- filename: 0g-labs-account-api-openapi.yml
  format: yaml
  label: 0G Labs Account API
  slug: 0g-labs-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0g-labs/openapi/0g-labs-account-api-openapi.yml
- filename: 0g-labs-api-key-api-openapi.yml
  format: yaml
  label: 0G Labs API Key API
  slug: 0g-labs-api-key-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0g-labs/openapi/0g-labs-api-key-api-openapi.yml
- filename: 0g-labs-inference-api-openapi.yml
  format: yaml
  label: 0G Labs Inference API
  slug: 0g-labs-inference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0g-labs/openapi/0g-labs-inference-api-openapi.yml
- filename: 0g-labs-models-api-openapi.yml
  format: yaml
  label: 0G Labs Models API
  slug: 0g-labs-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0g-labs/openapi/0g-labs-models-api-openapi.yml
- filename: 0g-labs-provider-api-openapi.yml
  format: yaml
  label: 0G Labs Provider API
  slug: 0g-labs-provider-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0g-labs/openapi/0g-labs-provider-api-openapi.yml
- filename: 0g-labs-service-types-api-openapi.yml
  format: yaml
  label: 0G Labs Service Types API
  slug: 0g-labs-service-types-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/0g-labs/openapi/0g-labs-service-types-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - BY
    - CU
    - IR
    - MM
    - KP
    - SD
    - SY
    served: []
    text: you are not located in, organized in, or a resident of any Restricted Territory (as defined below)... Restricted Territories means Belarus, Cuba, Iran, Myanmar (Burma), North Korea, Sudan, Syria, and the Crimea, Donetsk, and Luhansk regions of Ukraine
  entity_types:
  - text: you are at least eighteen (18) years of age, or such higher age as required by applicable law in your jurisdiction
    type: individual
  - text: If you are accessing or using the Services on behalf of a legal entity, you represent and warrant that you have the authority to bind that entity to these Terms
    type: business
  minimum_age:
    text: you are at least eighteen (18) years of age, or such higher age as required by applicable law in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Sanctions and illicit activity
    text: use the Services to engage in market manipulation, wash trading, fraud, money laundering, terrorist financing, or any other illicit activity
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- BY
- CU
- IR
- MM
- KP
- SD
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 0G Labs
provenance_date: '2026-11-09'
provider_name: 0G Labs
provider_slug: 0g-labs
slug: 0g-labs-eligibility
source_date: '2026-11-09'
source_filename: 0g-labs-eligibility.yml
source_heading: Eligibility
source_page: https://0g.ai/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 0G Labs\naid: 0g-labs\nurl: https://0g.ai/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - BY\n  - CU\n  - IR\n  - MM\n  - KP\n  - SD\n  - SY\n  text: you are not located in, organized in, or a resident of any Restricted Territory (as defined below)... Restricted\n    Territories means Belarus, Cuba, Iran, Myanmar (Burma), North Korea, Sudan, Syria, and the Crimea, Donetsk,\n    and Luhansk regions of Ukraine\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years of age, or such higher age as required by applicable law in your jurisdiction\n- type:\
  \ business\n  text: If you are accessing or using the Services on behalf of a legal entity, you represent and warrant that you\n    have the authority to bind that entity to these Terms\nrestricted_uses:\n- summary: Sanctions and illicit activity\n  text: use the Services to engage in market manipulation, wash trading, fraud, money laundering, terrorist financing,\n    or any other illicit activity\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age, or such higher age as required by applicable law in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/0g-labs/eligibility/0g-labs-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from 0G Labs's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Inference
- LLM
- GPU Compute
- Decentralized Compute
- Blockchain
- Web3
- EVM
- Decentralized Storage
- Data Availability
- OpenAI-Compatible
- Trusted Execution Environment
- Agent-Native
- Crypto Infrastructure
---
