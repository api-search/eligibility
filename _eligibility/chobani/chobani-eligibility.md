---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent and warrant that you are at least 13 years of age.
    value: '13'
  restricted_uses:
  - summary: unlawful purposes
    text: You may not use this Website (i) for any purpose that violates applicable federal, state or local laws, regulations or rules
  - summary: no unauthorized access or reverse engineering
    text: attempt to gain unauthorized access to this Website through hacking, password mining or any other means
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
name: Chobani
provenance_date: '2026-11-09'
provider_name: Chobani
provider_slug: chobani
slug: chobani-eligibility
source_date: '2026-11-09'
source_filename: chobani-eligibility.yml
source_heading: Eligibility
source_page: https://www.chobani.com/legal/website-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Chobani\naid: chobani\nurl: https://www.chobani.com/legal/website-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: unlawful purposes\n  text: You may not use this Website (i) for any purpose that violates applicable federal, state or local laws,\n    regulations or rules\n- summary: no unauthorized access or reverse engineering\n  text: attempt to gain unauthorized access to this Website through hacking, password mining or any other means\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n\
  \  value: '13'\n  text: You represent and warrant that you are at least 13 years of age.\n"
source_yaml_url: https://artifacts.apis.io/chobani/eligibility/chobani-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Chobani's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer Goods
- Consumer Packaged Goods
- Food Products
- Beverages
- Dairy
- Yogurt
- Coffee
- Manufacturing
- Food and Beverage
---
