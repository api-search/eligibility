---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bloomberg operates this site in the United States. Bloomberg makes no representation that the Service ... [is] appropriate or available for use in locations other than the United States.
  minimum_age:
    text: you are at least eighteen (18) years old
    value: '18'
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or regulation
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
name: Bloomberg News
provenance_date: '2026-11-09'
provider_name: Bloomberg News
provider_slug: bloomberg-news
slug: bloomberg-news-eligibility
source_date: '2026-11-09'
source_filename: bloomberg-news-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomberg News\naid: bloomberg-news\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Bloomberg operates this site in the United States. Bloomberg makes no representation that the Service ...\n    [is] appropriate or available for use in locations other than the United States.\nentity_types: []\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or\n    regulation\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-news/eligibility/bloomberg-news-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bloomberg News's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Business Intelligence
- Financial Services
- Market Data
- News
---
