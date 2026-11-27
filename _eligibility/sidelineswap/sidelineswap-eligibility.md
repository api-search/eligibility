---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Not stated, except that the Apple section represents the user is not located in a country subject to a U.S. Government embargo.
  entity_types:
  - text: The Service is available only to individuals who can form legally binding contracts under applicable law.
    type: individual
  minimum_age:
    text: the Service is not available to minors (people under the age of majority in their state or province of residence)
    value: age of majority
  restricted_uses:
  - summary: Illegal or prohibited items
    text: SidelineSwap prohibits the listing or sale of any Item that is illegal to sell under any applicable law, statute, ordinance, or regulation
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
name: SidelineSwap
provenance_date: '2026-11-10'
provider_name: SidelineSwap
provider_slug: sidelineswap
slug: sidelineswap-eligibility
source_date: '2026-11-10'
source_filename: sidelineswap-eligibility.yml
source_heading: Eligibility
source_page: https://sidelineswap.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: SidelineSwap\naid: sidelineswap\nurl: https://sidelineswap.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Not stated, except that the Apple section represents the user is not located in a country subject to a U.S.\n    Government embargo.\nentity_types:\n- type: individual\n  text: The Service is available only to individuals who can form legally binding contracts under applicable law.\nrestricted_uses:\n- summary: Illegal or prohibited items\n  text: SidelineSwap prohibits the listing or sale of any Item that is illegal to sell under any applicable\
  \ law,\n    statute, ordinance, or regulation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: the Service is not available to minors (people under the age of majority in their state or province of residence)\n"
source_yaml_url: https://artifacts.apis.io/sidelineswap/eligibility/sidelineswap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from SidelineSwap's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Marketplace
- Sports
- Sporting Goods
- E-Commerce
- Commerce
- Inventory
- Resale
- Consignment
---
