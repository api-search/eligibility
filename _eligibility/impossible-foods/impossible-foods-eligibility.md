---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: you are at least 13 years old
    value: '13'
  restricted_uses:
  - summary: Resale of purchased Products
    text: Unless you are a restaurant operator, you are not permitted to resell or otherwise use any of the Products you purchase for commercial purposes.
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
name: Impossible Foods
provenance_date: '2026-11-09'
provider_name: Impossible Foods
provider_slug: impossible-foods
slug: impossible-foods-eligibility
source_date: '2026-11-09'
source_filename: impossible-foods-eligibility.yml
source_heading: Eligibility
source_page: https://impossiblefoods.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Impossible Foods\naid: impossible-foods\nurl: https://impossiblefoods.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Resale of purchased Products\n  text: Unless you are a restaurant operator, you are not permitted to resell or otherwise use any of the Products\n    you purchase for commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you are at least 13 years old\n"
source_yaml_url: https://artifacts.apis.io/impossible-foods/eligibility/impossible-foods-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Impossible Foods's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Frontier Tech
- Food
- Food Technology
- Plant-Based
- Alternative Protein
- Consumer Packaged Goods
- Sustainability
- Food and Beverage
---
