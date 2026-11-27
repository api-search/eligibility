---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 18 years of age to use the Service.
    value: '18'
  restricted_uses:
  - summary: No personalized investment advice
    text: Nothing on this Service constitutes personalized investment advice, a recommendation to buy or sell any security, or a solicitation to invest.
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
name: Chart Library
provenance_date: '2026-11-09'
provider_name: Chart Library
provider_slug: chartlibrary-io
slug: chartlibrary-io-eligibility
source_date: '2026-11-09'
source_filename: chartlibrary-io-eligibility.yml
source_heading: Eligibility
source_page: https://chartlibrary.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chart Library\naid: chartlibrary-io\nurl: https://chartlibrary.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No personalized investment advice\n  text: Nothing on this Service constitutes personalized investment advice, a recommendation to buy or sell any\n    security, or a solicitation to invest.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/chartlibrary-io/eligibility/chartlibrary-io-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Chart Library's own page on 2026-11-09.
synthetic: false
tags:
- Finance
- Newsletters
- Stock Analysis
- Market Data
- Free Trial
---
