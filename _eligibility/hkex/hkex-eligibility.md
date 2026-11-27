---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Website is not directed at, and is not intended for distribution to or use by, any person in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: AI training or fine-tuning
    text: including the development, training, fine-tuning or validation of artificial intelligence (“AI”) systems or models
  - summary: use as a benchmark
    text: use the Information as a benchmark or in connection with the determination of a benchmark
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
name: HKEX
provenance_date: '2026-11-09'
provider_name: HKEX
provider_slug: hkex
slug: hkex-eligibility
source_date: '2026-11-09'
source_filename: hkex-eligibility.yml
source_heading: Eligibility
source_page: https://www.hkex.com.hk/Global/Exchange/Terms-of-Use?sc_lang=en
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HKEX\naid: hkex\nurl: https://www.hkex.com.hk/Global/Exchange/Terms-of-Use?sc_lang=en\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Website is not directed at, and is not intended for distribution to or use by, any person in any jurisdiction\n    or country where such distribution or use would be contrary to law or regulation\nentity_types: []\nrestricted_uses:\n- summary: AI training or fine-tuning\n  text: including the development, training, fine-tuning or validation of artificial intelligence (“AI”) systems\n    or models\n- summary: use as a benchmark\n  text: use the\
  \ Information as a benchmark or in connection with the determination of a benchmark\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hkex/eligibility/hkex-eligibility.yml
stated_fields:
- countries
- restricted_uses
summary_line: 3 quoted statements, read from HKEX's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Market Data
- Stocks
- Derivatives
- Exchange
- Real-Time
- Historical Data
- Order Book
- Reference Data
- IPO
---
