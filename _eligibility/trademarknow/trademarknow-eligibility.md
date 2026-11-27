---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: A user is defined as any individual, company, law practice or other entity accessing any Service or other information at the Site
    type: individual
  - text: A user is defined as any individual, company, law practice or other entity accessing any Service or other information at the Site
    type: business
  - text: A user is defined as any individual, company, law practice or other entity accessing any Service or other information at the Site
    type: other
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Reproduction barred for trademark research businesses
    text: limited reproduction is not allowed, if the recipient/user is a company, partnership, or entity in the trademark research business
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
name: TrademarkNow
provenance_date: '2026-11-10'
provider_name: TrademarkNow
provider_slug: trademarknow
slug: trademarknow-eligibility
source_date: '2026-11-10'
source_filename: trademarknow-eligibility.yml
source_heading: Eligibility
source_page: https://corsearch.com/user-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TrademarkNow\naid: trademarknow\nurl: https://corsearch.com/user-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: A user is defined as any individual, company, law practice or other entity accessing any Service or other\n    information at the Site\n- type: business\n  text: A user is defined as any individual, company, law practice or other entity accessing any Service or other\n    information at the Site\n- type: other\n  text: A user is defined as any individual, company, law practice or other entity accessing any Service\
  \ or other\n    information at the Site\nrestricted_uses:\n- summary: Reproduction barred for trademark research businesses\n  text: limited reproduction is not allowed, if the recipient/user is a company, partnership, or entity in the trademark\n    research business\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/trademarknow/eligibility/trademarknow-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from TrademarkNow's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Trademarks
- Intellectual Property
- Legal Tech
- Brand Protection
- Trademark Search
- Artificial Intelligence
- Software-as-a-Service
---
