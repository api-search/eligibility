---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - US
    - GB
    served: []
    text: By using the Service, you agree that you are not a citizen of, or based in, the United States of America or the United Kingdom.
  entity_types:
  - text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    type: individual
  minimum_age:
    text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.
    value: '18'
  restricted_uses:
  - summary: Sanctioned persons and addresses
    text: You agree that we have the right to restrict access to the Service via any technically available methods if we suspect, in our sole discretion, that any of the aforementioned categories have been implicated.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- US
- GB
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cozy Finance
provenance_date: '2026-11-09'
provider_name: Cozy Finance
provider_slug: cozy-finance
slug: cozy-finance-eligibility
source_date: '2026-11-09'
source_filename: cozy-finance-eligibility.yml
source_heading: Eligibility
source_page: https://cozy-finance.webflow.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cozy Finance\naid: cozy-finance\nurl: https://cozy-finance.webflow.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - US\n  - GB\n  text: By using the Service, you agree that you are not a citizen of, or based in, the United States of America\n    or the United Kingdom.\nentity_types:\n- type: individual\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\nrestricted_uses:\n- summary: Sanctioned persons and addresses\n  text: You agree that we have the right to restrict access to the Service via any technically available\
  \ methods\n    if we suspect, in our sole discretion, that any of the aforementioned categories have been implicated.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If you are under 18 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/cozy-finance/eligibility/cozy-finance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Cozy Finance's own page on 2026-11-09.
synthetic: false
tags:
- Company
- DeFi
- Risk Management
- Smart Contracts
- Ethereum
- Insurance
- Blockchain
- Web3
---
