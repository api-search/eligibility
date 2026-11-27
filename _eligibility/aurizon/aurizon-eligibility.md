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
  - summary: Content only for performing duties
    text: You must use the content (or any part) ONLY for the purpose of performing your duties.
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
name: Aurizon
provenance_date: '2026-11-09'
provider_name: Aurizon
provider_slug: aurizon
slug: aurizon-eligibility
source_date: '2026-11-09'
source_filename: aurizon-eligibility.yml
source_heading: Eligibility
source_page: https://aurizon.com.au/terms-and-conditions-for-customer-portal
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aurizon\naid: aurizon\nurl: https://aurizon.com.au/terms-and-conditions-for-customer-portal\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Content only for performing duties\n  text: You must use the content (or any part) ONLY for the purpose of performing your duties.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/aurizon/eligibility/aurizon-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Aurizon's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Rail Freight
- Logistics
- Transportation
- Mining
- Australia
- Supply Chain
---
