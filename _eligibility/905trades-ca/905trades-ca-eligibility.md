---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Service limits
    text: It does not sell parts, diagnose vehicles, provide mortgage advice or decide whether a person qualifies for a financial product.
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
name: 905 Trades
provenance_date: '2026-11-09'
provider_name: 905 Trades
provider_slug: 905trades-ca
slug: 905trades-ca-eligibility
source_date: '2026-11-09'
source_filename: 905trades-ca-eligibility.yml
source_heading: Eligibility
source_page: https://905trades.ca/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 905 Trades\naid: 905trades-ca\nurl: https://905trades.ca/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Service limits\n  text: It does not sell parts, diagnose vehicles, provide mortgage advice or decide whether a person qualifies\n    for a financial product.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/905trades-ca/eligibility/905trades-ca-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from 905 Trades's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Home Services
- Trade
- Canada
- GTA
---
