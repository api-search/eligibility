---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    type: individual
  minimum_age:
    text: Service is intended only for access and use by individuals at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Free Plan API key limit
    text: Use more than one API key per application on the Free Plan.
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
name: Defined
provenance_date: '2026-11-09'
provider_name: Defined
provider_slug: defined
slug: defined-eligibility
source_date: '2026-11-09'
source_filename: defined-eligibility.yml
source_heading: Eligibility
source_page: https://dashboard.codex.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Defined\naid: defined\nurl: https://dashboard.codex.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\nrestricted_uses:\n- summary: Free Plan API key limit\n  text: Use more than one API key per application on the Free Plan.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Service is intended only for access and use by individuals at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/defined/eligibility/defined-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Defined's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cryptocurrency
- Blockchain
- DeFi
- Market Data
- Trading
- GraphQL
- Web3
- Prediction Markets
---
