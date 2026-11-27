---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may not access or use the Services or accept the Agreement if you are not at least 18 years old.
    type: individual
  minimum_age:
    text: You may not access or use the Services or accept the Agreement if you are not at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Unlawful or abusive use
    text: use the service for any unlawful purpose or for the promotion of illegal activities
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
name: StockTrim
provenance_date: '2026-11-10'
provider_name: StockTrim
provider_slug: stocktrim
slug: stocktrim-eligibility
source_date: '2026-11-10'
source_filename: stocktrim-eligibility.yml
source_heading: Eligibility
source_page: https://www.stocktrim.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StockTrim\naid: stocktrim\nurl: https://www.stocktrim.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may not access or use the Services or accept the Agreement if you are not at least 18 years old.\nrestricted_uses:\n- summary: Unlawful or abusive use\n  text: use the service for any unlawful purpose or for the promotion of illegal activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may not access or use the Services or accept the Agreement\
  \ if you are not at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/stocktrim/eligibility/stocktrim-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from StockTrim's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Inventory
- Forecasting
- Supply Chain
- Software-as-a-Service
---
