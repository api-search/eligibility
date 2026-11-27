---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: To create an account, you must be at least 18 years old and you must provide truthful and accurate information about yourself.
    type: individual
  minimum_age:
    text: To create an account, you must be at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Unlawful or rights-infringing use
    text: Please do not use the Sites in a way that violates any laws, infringes on anyone’s rights, is offensive, or interferes with the Sites
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
name: TradeLanes
provenance_date: '2026-11-10'
provider_name: TradeLanes
provider_slug: tradelanes
slug: tradelanes-eligibility
source_date: '2026-11-10'
source_filename: tradelanes-eligibility.yml
source_heading: Eligibility
source_page: https://www.tradelanes.co/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TradeLanes\naid: tradelanes\nurl: https://www.tradelanes.co/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: To create an account, you must be at least 18 years old and you must provide truthful and accurate information\n    about yourself.\nrestricted_uses:\n- summary: Unlawful or rights-infringing use\n  text: Please do not use the Sites in a way that violates any laws, infringes on anyone’s rights, is offensive,\n    or interferes with the Sites\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '18'\n  text: To create an account, you must be at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/tradelanes/eligibility/tradelanes-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from TradeLanes's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Logistics
- Shipping
- Trade
- Supply Chain
- Export
- Vessel Schedules
- Freight Forwarding
---
