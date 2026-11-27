---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Each account is for a single individual.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Unauthorized bank connections
    text: Connect bank accounts that do not belong to you or for which you lack authorization
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
name: Shelter
provenance_date: '2026-11-10'
provider_name: Shelter
provider_slug: shelter-money
slug: shelter-money-eligibility
source_date: '2026-11-10'
source_filename: shelter-money-eligibility.yml
source_heading: Eligibility
source_page: https://shelter.money/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shelter\naid: shelter-money\nurl: https://shelter.money/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Each account is for a single individual.\nrestricted_uses:\n- summary: Unauthorized bank connections\n  text: Connect bank accounts that do not belong to you or for which you lack authorization\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/shelter-money/eligibility/shelter-money-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Shelter's own page on 2026-11-10.
synthetic: false
tags:
- Personal Finance
- Budgeting
- Fintech
- MCP
- AI Agents
- Cash Flow Forecasting
---
