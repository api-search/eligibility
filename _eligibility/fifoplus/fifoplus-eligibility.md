---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served:
    - SA
    text: you must be a legal entity duly registered under the laws of Kingdom of Saudi Arabia
  entity_types:
  - text: be a legal entity duly registered under the laws of Kingdom of Saudi Arabia; in the case of the Sellers, have a current trade license permitting you to sell the Goods
    type: business
  minimum_age:
    text: null
    value: null
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
name: FIFOplus
provenance_date: '2026-11-09'
provider_name: FIFOplus
provider_slug: fifoplus
slug: fifoplus-eligibility
source_date: '2026-11-09'
source_filename: fifoplus-eligibility.yml
source_heading: Eligibility
source_page: https://www.fifoplus.com/terms-and-condition
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FIFOplus\naid: fifoplus\nurl: https://www.fifoplus.com/terms-and-condition\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - SA\n  excluded: []\n  text: you must be a legal entity duly registered under the laws of Kingdom of Saudi Arabia\nentity_types:\n- type: business\n  text: be a legal entity duly registered under the laws of Kingdom of Saudi Arabia; in the case of the Sellers,\n    have a current trade license permitting you to sell the Goods\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fifoplus/eligibility/fifoplus-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from FIFOplus's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Procurement
- Food and Beverage
- B2B
- Marketplace
- E-Commerce
- HORECA
- Supply Chain
- Saudi Arabia
- Restaurant
---
