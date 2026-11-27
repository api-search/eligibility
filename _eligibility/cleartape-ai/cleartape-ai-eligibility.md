---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: An account is for one person.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Unlawful use
    text: use it for anything unlawful
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
name: Clear Tape
provenance_date: '2026-11-09'
provider_name: Clear Tape
provider_slug: cleartape-ai
slug: cleartape-ai-eligibility
source_date: '2026-11-09'
source_filename: cleartape-ai-eligibility.yml
source_heading: Eligibility
source_page: https://cleartape.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clear Tape\naid: cleartape-ai\nurl: https://cleartape.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: An account is for one person.\nrestricted_uses:\n- summary: Unlawful use\n  text: use it for anything unlawful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/cleartape-ai/eligibility/cleartape-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Clear Tape's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Stock Screener
- Data
- Backtesting
- Free Tier
---
