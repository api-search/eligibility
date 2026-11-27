---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Free shipping on all US orders
  entity_types:
  - text: you represent that you are at least the age of majority in your state or province of residence
    type: individual
  - text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers, resellers or distributors.
    type: business
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Illegal or unauthorized use
    text: You may not use our products for any illegal or unauthorized purpose
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
name: Public Goods
provenance_date: '2026-11-10'
provider_name: Public Goods
provider_slug: public-goods
slug: public-goods-eligibility
source_date: '2026-11-10'
source_filename: public-goods-eligibility.yml
source_heading: Eligibility
source_page: https://www.publicgoods.com/pages/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Public Goods\naid: public-goods\nurl: https://www.publicgoods.com/pages/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Free shipping on all US orders\nentity_types:\n- type: individual\n  text: you represent that you are at least the age of majority in your state or province of residence\n- type: business\n  text: We reserve the right to limit or prohibit orders that, in our sole judgment, appear to be placed by dealers,\n    resellers or distributors.\nrestricted_uses:\n- summary: Illegal or unauthorized use\n  text: You may not use our products for any illegal\
  \ or unauthorized purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/public-goods/eligibility/public-goods-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Public Goods's own page on 2026-11-10.
synthetic: false
tags:
- Company
- E-Commerce
- Retail
- Consumer Goods
- Household
- Personal Care
- Sustainability
- Direct to Consumer
---
