---
api_specs:
- filename: postman
  format: yaml
  label: Nasdaq Data Link REST API for Real-Time or Delayed Data
  slug: nasdaq-data-link-rest-api-for-real-time-or-delayed-data
  spec_type: Postman
  url: https://github.com/Nasdaq/NasdaqCloudDataService-REST-API/tree/main/restapi/postman
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
  - summary: No SaaS/cloud platforms outside Client control
    text: use or permit the use of the Nasdaq Information in any software-as-a-service (SaaS), cloud-based, distributed, or other technology platform
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
name: Nasdaq Data Link
provenance_date: '2026-11-10'
provider_name: Nasdaq Data Link
provider_slug: nasdaq-data-link
slug: nasdaq-data-link-eligibility
source_date: '2026-11-10'
source_filename: nasdaq-data-link-eligibility.yml
source_heading: Eligibility
source_page: https://data.nasdaq.com/termsandconditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Nasdaq Data Link\naid: nasdaq-data-link\nurl: https://data.nasdaq.com/termsandconditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No SaaS/cloud platforms outside Client control\n  text: use or permit the use of the Nasdaq Information in any software-as-a-service (SaaS), cloud-based, distributed,\n    or other technology platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/nasdaq-data-link/eligibility/nasdaq-data-link-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Nasdaq Data Link's own page on 2026-11-10.
synthetic: false
tags:
- Financial Data
- Stock Market
- Market Data
- Economic Data
- Alternative Data
- Time Series
- Open Data
- Public APIs
---
