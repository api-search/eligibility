---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Laundryheap+ and Laundryheap+ Pro are currently available in all Laundryheap service countries.
  entity_types:
  - text: Subscriptions are available for personal, non-commercial use.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use excludes profit-loss liability
    text: If you use the Services for any commercial, business or re-sale purpose, We have no liability to you for any loss of profit, loss of business, business interruption, or loss of business opportunity.
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
name: Laundryheap
provenance_date: '2026-11-09'
provider_name: Laundryheap
provider_slug: laundryheap
slug: laundryheap-eligibility
source_date: '2026-11-09'
source_filename: laundryheap-eligibility.yml
source_heading: Eligibility
source_page: https://www.laundryheap.com/en-us/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Laundryheap\naid: laundryheap\nurl: https://www.laundryheap.com/en-us/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Laundryheap+ and Laundryheap+ Pro are currently available in all Laundryheap service countries.\nentity_types:\n- type: individual\n  text: Subscriptions are available for personal, non-commercial use.\nrestricted_uses:\n- summary: Commercial use excludes profit-loss liability\n  text: If you use the Services for any commercial, business or re-sale purpose, We have no liability to you for\n    any loss of profit, loss of business, business interruption, or loss\
  \ of business opportunity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/laundryheap/eligibility/laundryheap-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Laundryheap's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Laundry
- Dry Cleaning
- On-Demand Services
- Logistics
- Last Mile Delivery
- Consumer Services
- Hospitality
- Ordering
- GraphQL
- OAuth
- Authentication
---
