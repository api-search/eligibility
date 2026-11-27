---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The page names no served countries. It refers generally to 'any country which the United States has embargoed for goods or services' without naming any.
  entity_types:
  - text: you are at least eighteen (18) years of age
    type: individual
  minimum_age:
    text: you are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: Commercial use prohibited
    text: you may not access or use the Services for any commercial purpose whatsoever
  - summary: Export and sanctions restrictions
    text: are not located in, under the control of, or a national or resident of any country which the United States has embargoed for goods or services
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
name: CafePress
provenance_date: '2026-11-09'
provider_name: CafePress
provider_slug: cafepress
slug: cafepress-eligibility
source_date: '2026-11-09'
source_filename: cafepress-eligibility.yml
source_heading: Eligibility
source_page: https://www.cafepress.com/p/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CafePress\naid: cafepress\nurl: https://www.cafepress.com/p/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The page names no served countries. It refers generally to 'any country which the United States has embargoed\n    for goods or services' without naming any.\nentity_types:\n- type: individual\n  text: you are at least eighteen (18) years of age\nrestricted_uses:\n- summary: Commercial use prohibited\n  text: you may not access or use the Services for any commercial purpose whatsoever\n- summary: Export and sanctions restrictions\n  text:\
  \ are not located in, under the control of, or a national or resident of any country which the United States\n    has embargoed for goods or services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/cafepress/eligibility/cafepress-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CafePress's own page on 2026-11-09.
synthetic: false
tags:
- Company
- E-Commerce
- Print on Demand
- Custom Merchandise
- Online Marketplace
---
