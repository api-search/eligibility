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
  - summary: No financial or transaction advice
    text: FXpeek does not provide financial, investment, trading, tax, accounting, legal, or transaction advice.
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
name: fxpeek-com
provenance_date: '2026-11-09'
provider_name: fxpeek-com
provider_slug: fxpeek-com
slug: fxpeek-com-eligibility
source_date: '2026-11-09'
source_filename: fxpeek-com-eligibility.yml
source_heading: Eligibility
source_page: https://fxpeek.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fxpeek-com\naid: fxpeek-com\nurl: https://fxpeek.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No financial or transaction advice\n  text: FXpeek does not provide financial, investment, trading, tax, accounting, legal, or transaction advice.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fxpeek-com/eligibility/fxpeek-com-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from fxpeek-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Finance
- Currency
- Data
---
