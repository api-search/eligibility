---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into or accepting these terms on behalf of a legal entity, you represent and warrant that you have the authority to bind such entity and its affiliates to these terms.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use or access certain parts of the product, you must successfully register an account with Datalego.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kite
provenance_date: '2026-11-09'
provider_name: Kite
provider_slug: kite
slug: kite-eligibility
source_date: '2026-11-09'
source_filename: kite-eligibility.yml
source_heading: Eligibility
source_page: https://gokite.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kite\naid: kite\nurl: https://gokite.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into or accepting these terms on behalf of a legal entity, you represent and warrant\n    that you have the authority to bind such entity and its affiliates to these terms.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order to use or access certain parts of the product, you must successfully register an account with Datalego.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/kite/eligibility/kite-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 2 quoted statements, read from Kite's own page on 2026-11-09.
synthetic: false
tags:
- Agentic Payments
- AI Agents
- x402
- Stablecoins
- Blockchain
- EVM
- Layer 1
- Machine-to-Machine
- Identity
- Payments
- JSON-RPC
- Account Abstraction
---
