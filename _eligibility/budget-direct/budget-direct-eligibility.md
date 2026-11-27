---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - AU
    text: The information on this Website is provided for Australian residents only. ... Only Australian residents are able to buy insurance from us.
  entity_types:
  - text: genuine customers and potential customers interested in purchasing a product from us for themselves or immediate family (with their consent)
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No commercial use
    text: 'You must not use the Website or its Content: for commercial purposes (including, without limitation, for a person''s competitive advantage or to our competitive disadvantage)'
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
name: Budget Direct
provenance_date: '2026-11-09'
provider_name: Budget Direct
provider_slug: budget-direct
slug: budget-direct-eligibility
source_date: '2026-11-09'
source_filename: budget-direct-eligibility.yml
source_heading: Eligibility
source_page: https://www.budgetdirect.com.au/website-terms-of-use.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Budget Direct\naid: budget-direct\nurl: https://www.budgetdirect.com.au/website-terms-of-use.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - AU\n  excluded: []\n  text: The information on this Website is provided for Australian residents only. ... Only Australian residents\n    are able to buy insurance from us.\nentity_types:\n- type: individual\n  text: genuine customers and potential customers interested in purchasing a product from us for themselves or immediate\n    family (with their consent)\nrestricted_uses:\n- summary: No commercial use\n  text: 'You must not use the Website or its Content:\
  \ for commercial purposes (including, without limitation, for\n    a person''s competitive advantage or to our competitive disadvantage)'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/budget-direct/eligibility/budget-direct-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Budget Direct's own page on 2026-11-09.
synthetic: false
tags:
- Insurance
- Australia
- Property and Casualty
- Direct to Consumer Insurance
- Auto Insurance
- Home Insurance
- Travel Insurance
- Life Insurance
- Underwriting
- Claims
- Carrier
---
