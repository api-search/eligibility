---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Shriram Finance Limited makes no representation that the Services are appropriate or available for use in locations outside India.
  entity_types:
  - text: Be at least [18] years of age to use the Services; by using our Services you warrant and represent to us that you are at least [18] years of age.
    type: individual
  minimum_age:
    text: Be at least [18] years of age to use the Services
    value: '18'
  restricted_uses:
  - summary: Illegal use and disruption
    text: You will not use the Website or Services for illegal purposes.
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
name: Shriram Finance
provenance_date: '2026-11-10'
provider_name: Shriram Finance
provider_slug: shriramfinance
slug: shriramfinance-eligibility
source_date: '2026-11-10'
source_filename: shriramfinance-eligibility.yml
source_heading: Eligibility
source_page: https://www.shriramfinance.in/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shriram Finance\naid: shriramfinance\nurl: https://www.shriramfinance.in/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Shriram Finance Limited makes no representation that the Services are appropriate or available for use in\n    locations outside India.\nentity_types:\n- type: individual\n  text: Be at least [18] years of age to use the Services; by using our Services you warrant and represent to us\n    that you are at least [18] years of age.\nrestricted_uses:\n- summary: Illegal use and disruption\n  text: You will not use the Website or Services for illegal\
  \ purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Be at least [18] years of age to use the Services\n"
source_yaml_url: https://artifacts.apis.io/shriramfinance/eligibility/shriramfinance-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Shriram Finance's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Financial Services
- NBFC
- Lending
- Insurance
- Fixed Deposits
- Bill Payments
- UPI
- Payments
- India
---
