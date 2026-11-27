---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You represent that you are of sufficient legal age to use the website or mobile application and to create binding legal obligations
    value: null
  restricted_uses:
  - summary: Unlawful or prohibited content and conduct
    text: You may not use an Ameren Site for any fraudulent or unlawful purpose
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
name: Ameren
provenance_date: '2026-11-09'
provider_name: Ameren
provider_slug: ameren
slug: ameren-eligibility
source_date: '2026-11-09'
source_filename: ameren-eligibility.yml
source_heading: Eligibility
source_page: https://www.ameren.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ameren\naid: ameren\nurl: https://www.ameren.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Unlawful or prohibited content and conduct\n  text: You may not use an Ameren Site for any fraudulent or unlawful purpose\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You represent that you are of sufficient legal age to use the website or mobile application and to create\n    binding legal obligations\n"
source_yaml_url: https://artifacts.apis.io/ameren/eligibility/ameren-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Ameren's own page on 2026-11-09.
synthetic: false
tags:
- Utility
- Energy
- Electric
- Natural Gas
- Smart Grid
- Green Button
- Renewable Energy
- Fortune 500
---
