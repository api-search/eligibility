---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: By using this Site, you also represent and agree that you are at least 18 years of age
    type: individual
  minimum_age:
    text: you are at least 18 years of age, or that you have given us your consent to allow any of your minor dependents to use this Site
    value: '18'
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
name: Conagra Brands
provenance_date: '2026-11-09'
provider_name: Conagra Brands
provider_slug: conagra-brands
slug: conagra-brands-eligibility
source_date: '2026-11-09'
source_filename: conagra-brands-eligibility.yml
source_heading: Eligibility
source_page: https://www.conagrabrands.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Conagra Brands\naid: conagra-brands\nurl: https://www.conagrabrands.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: By using this Site, you also represent and agree that you are at least 18 years of age\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age, or that you have given us your consent to allow any of your minor dependents\n    to use this Site\n"
source_yaml_url: https://artifacts.apis.io/conagra-brands/eligibility/conagra-brands-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Conagra Brands's own page on 2026-11-09.
synthetic: false
tags:
- Branded Foods
- Consumer Packaged Goods
- Food Service
- Fortune 500
- Frozen Foods
- Grocery
- OData
- Product Data
- Food and Beverage
---
