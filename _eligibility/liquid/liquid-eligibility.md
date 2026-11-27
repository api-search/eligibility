---
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    served: []
    text: You are not a resident, national, or agent of the Crimea region, Cuba, Iran, North Korea, Syria, or any other country to which the United States, the United Kingdom, or the European Union embargoes goods or imposes similar sanctions.
  entity_types:
  - text: You must be at least eighteen years old.
    type: individual
  minimum_age:
    text: You must be at least eighteen years old.
    value: '18'
  restricted_uses:
  - summary: Illegal or illicit activity
    text: you will not use our Services to conduct any illegal or illicit activity.
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You acknowledge that the operator and its partners may perform Know Your Customer (“KYC”) procedures on the information you provide, as required by internal policies and as required by applicable guidelines or regulations.
excluded_countries:
- CU
- IR
- KP
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Liquid
provenance_date: '2026-11-09'
provider_name: Liquid
provider_slug: liquid
slug: liquid-eligibility
source_date: '2026-11-09'
source_filename: liquid-eligibility.yml
source_heading: Eligibility
source_page: https://www.liquid.trade/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Liquid\naid: liquid\nurl: https://www.liquid.trade/termsofservice\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  text: You are not a resident, national, or agent of the Crimea region, Cuba, Iran, North Korea, Syria, or any\n    other country to which the United States, the United Kingdom, or the European Union embargoes goods or imposes\n    similar sanctions.\nentity_types:\n- type: individual\n  text: You must be at least eighteen years old.\nrestricted_uses:\n- summary: Illegal or illicit activity\n  text: you will not use our Services to conduct any illegal\
  \ or illicit activity.\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You acknowledge that the operator and its partners may perform Know Your Customer (“KYC”) procedures on\n    the information you provide, as required by internal policies and as required by applicable guidelines or regulations.\nminimum_age:\n  value: '18'\n  text: You must be at least eighteen years old.\n"
source_yaml_url: https://artifacts.apis.io/liquid/eligibility/liquid-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Liquid's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Crypto Defi
- Trading
- Perpetual Futures
- Prediction Markets
- Fintech
- MCP
- Agentic Commerce
- OAuth
- Authentication
---
