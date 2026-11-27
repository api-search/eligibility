---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - IN
    text: As we are providing Services in the selected cities of India
  entity_types:
  - text: Only individuals who are 18 years of age or older may use the Platform and avail the Services.
    type: individual
  minimum_age:
    text: Only individuals who are 18 years of age or older may use the Platform and avail the Services.
    value: '18'
  restricted_uses:
  - summary: No resale of purchased goods
    text: Goods and services purchased from the Platform are intended for your personal use and you represent that the same are not for resale
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
name: Swiggy
provenance_date: '2026-11-10'
provider_name: Swiggy
provider_slug: swiggy
slug: swiggy-eligibility
source_date: '2026-11-10'
source_filename: swiggy-eligibility.yml
source_heading: Eligibility
source_page: https://www.swiggy.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Swiggy\naid: swiggy\nurl: https://www.swiggy.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - IN\n  excluded: []\n  text: As we are providing Services in the selected cities of India\nentity_types:\n- type: individual\n  text: Only individuals who are 18 years of age or older may use the Platform and avail the Services.\nrestricted_uses:\n- summary: No resale of purchased goods\n  text: Goods and services purchased from the Platform are intended for your personal use and you represent that\n    the same are not for resale\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Only individuals who are 18 years of age or older may use the Platform and avail the Services.\n"
source_yaml_url: https://artifacts.apis.io/swiggy/eligibility/swiggy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Swiggy's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Food Delivery
- Quick Commerce
- Grocery Delivery
- Logistics
- E-Commerce
- India
- Restaurant
---
