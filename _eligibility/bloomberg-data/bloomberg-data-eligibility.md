---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Bloomberg operates this site in the United States. Bloomberg makes no representation that the Service ... are appropriate or available for use in locations other than the United States.
  minimum_age:
    text: you are at least eighteen (18) years old.
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or regulation, or in any manner inconsistent with the TOS.
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
name: Bloomberg Data
provenance_date: '2026-11-09'
provider_name: Bloomberg Data
provider_slug: bloomberg-data
slug: bloomberg-data-eligibility
source_date: '2026-11-09'
source_filename: bloomberg-data-eligibility.yml
source_heading: Eligibility
source_page: https://www.bloomberg.com/notices/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Bloomberg Data\naid: bloomberg-data\nurl: https://www.bloomberg.com/notices/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: Bloomberg operates this site in the United States. Bloomberg makes no representation that the Service ...\n    are appropriate or available for use in locations other than the United States.\nentity_types: []\nrestricted_uses:\n- summary: Illegal purposes\n  text: You may not use the Service for any illegal purpose, for the facilitation of the violation of any law or\n    regulation, or in any manner inconsistent with the TOS.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years old.\n"
source_yaml_url: https://artifacts.apis.io/bloomberg-data/eligibility/bloomberg-data-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Bloomberg Data's own page on 2026-11-09.
synthetic: false
tags:
- Analytics
- Financial Services
- Market Data
- News
- Real-Time Data
- Trading
---
