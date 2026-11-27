---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: As a consumer, you may withdraw from this contract within fourteen (14) days without stating a reason.
    type: individual
  - text: Exclusive jurisdiction for business customers lies with the courts of Freiburg im Breisgau, Germany.
    type: business
  minimum_age:
    text: You must be at least 18 years old to create an account.
    value: '18'
  restricted_uses:
  - summary: Illegal activity or market manipulation
    text: Using the Service for illegal activities or market manipulation.
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
name: Algo Trade Analytics
provenance_date: '2026-11-09'
provider_name: Algo Trade Analytics
provider_slug: algo-trade-analytics-com
slug: algo-trade-analytics-com-eligibility
source_date: '2026-11-09'
source_filename: algo-trade-analytics-com-eligibility.yml
source_heading: Eligibility
source_page: https://algo-trade-analytics.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Algo Trade Analytics\naid: algo-trade-analytics-com\nurl: https://algo-trade-analytics.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: As a consumer, you may withdraw from this contract within fourteen (14) days without stating a reason.\n- type: business\n  text: Exclusive jurisdiction for business customers lies with the courts of Freiburg im Breisgau, Germany.\nrestricted_uses:\n- summary: Illegal activity or market manipulation\n  text: Using the Service for illegal activities or market manipulation.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/algo-trade-analytics-com/eligibility/algo-trade-analytics-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Algo Trade Analytics's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Trading
- Artificial Intelligence
- Analytics
- Backtesting
---
