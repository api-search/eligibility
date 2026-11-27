---
claim_count: 2
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
  - summary: Illegal purposes
    text: not to use the Website for illegal purposes
  - summary: Interference with systems
    text: not to interfere with, trespass on or disrupt the networks or computers and equipment connected to the Website
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
name: IEX
provenance_date: '2026-11-09'
provider_name: IEX
provider_slug: iex
slug: iex-eligibility
source_date: '2026-11-09'
source_filename: iex-eligibility.yml
source_heading: Eligibility
source_page: https://www.iex.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: IEX\naid: iex\nurl: https://www.iex.io/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: not to use the Website for illegal purposes\n- summary: Interference with systems\n  text: not to interfere with, trespass on or disrupt the networks or computers and equipment connected to the Website\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/iex/eligibility/iex-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 2 quoted statements, read from IEX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Fintech
- Stock Exchange
- Market Data
- Trading
- Stocks
- Options
- Financial Services
- Market Infrastructure
---
