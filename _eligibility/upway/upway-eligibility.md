---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Upway ships Products purchased via the Services to street addresses within the United States (except Alaska, Hawaii and US territories).
  entity_types:
  - text: 'YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THIS AGREEMENT IF: (A) YOU ARE NOT AT OR OVER THE AGE OF MAJORITY IN YOUR STATE'
    type: individual
  minimum_age:
    text: 'YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THIS AGREEMENT IF: (A) YOU ARE NOT AT OR OVER THE AGE OF MAJORITY IN YOUR STATE'
    value: age of majority in your state
  restricted_uses:
  - summary: Export restrictions
    text: The Services and Products may not be exported or re-exported (a) into any United States embargoed countries, or (b) to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals
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
name: Upway
provenance_date: '2026-11-10'
provider_name: Upway
provider_slug: upway
slug: upway-eligibility
source_date: '2026-11-10'
source_filename: upway-eligibility.yml
source_heading: Eligibility
source_page: https://upway.co/policies/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Upway\naid: upway\nurl: https://upway.co/policies/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Upway ships Products purchased via the Services to street addresses within the United States (except Alaska,\n    Hawaii and US territories).\nentity_types:\n- type: individual\n  text: 'YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THIS AGREEMENT IF: (A) YOU ARE NOT AT OR OVER THE AGE\n    OF MAJORITY IN YOUR STATE'\nrestricted_uses:\n- summary: Export restrictions\n  text: The Services and Products may not be exported or re-exported (a) into any United States embargoed\
  \ countries,\n    or (b) to anyone on the U.S. Treasury Department’s list of Specially Designated Nationals\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority in your state\n  text: 'YOU MAY NOT ACCESS OR USE THE SERVICES OR ACCEPT THIS AGREEMENT IF: (A) YOU ARE NOT AT OR OVER THE AGE\n    OF MAJORITY IN YOUR STATE'\n"
source_yaml_url: https://artifacts.apis.io/upway/eligibility/upway-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Upway's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Marketplace
- Agentic Commerce
- MCP
- Universal Commerce Protocol
- Electric Bikes
- Micromobility
- Circular Economy
- Refurbished Goods
- Shopping Agents
---
