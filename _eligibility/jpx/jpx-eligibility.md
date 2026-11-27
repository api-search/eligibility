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
  - summary: Commercial use of website data
    text: The collection of data or secondary use of information from this website for commercial purposes is strictly prohibited, unless JPX has granted prior permission or authorized such use under a paid contract.
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
name: JPX (Japan Exchange Group)
provenance_date: '2026-11-09'
provider_name: JPX (Japan Exchange Group)
provider_slug: jpx
slug: jpx-eligibility
source_date: '2026-11-09'
source_filename: jpx-eligibility.yml
source_heading: Eligibility
source_page: https://www.jpx.co.jp/english/term-of-use/index.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: JPX (Japan Exchange Group)\naid: jpx\nurl: https://www.jpx.co.jp/english/term-of-use/index.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Commercial use of website data\n  text: The collection of data or secondary use of information from this website for commercial purposes is strictly\n    prohibited, unless JPX has granted prior permission or authorized such use under a paid contract.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/jpx/eligibility/jpx-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from JPX (Japan Exchange Group)'s own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Stocks
- Exchange
- Trading
- Derivatives
- Indices
- Reference Data
- Japan
---
