---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - CA
    text: Live nationwide, more added daily British Columbia Alberta Saskatchewan Manitoba Ontario Quebec Nova Scotia New Brunswick Newfoundland & Labrador Prince Edward Island Yukon Northwest Territories
  entity_types:
  - text: You must be at least 18 years of age (or the age of majority in your province of residence, whichever is greater) to create an account or place an Order.
    type: individual
  minimum_age:
    text: You must be at least 18 years of age (or the age of majority in your province of residence, whichever is greater)
    value: '18'
  restricted_uses:
  - summary: Unlawful or fraudulent use
    text: Use the Platform for any unlawful purpose or in violation of any applicable laws or regulations.
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
name: Canuck Eats
provenance_date: '2026-11-09'
provider_name: Canuck Eats
provider_slug: canuckeats-com
slug: canuckeats-com-eligibility
source_date: '2026-11-09'
source_filename: canuckeats-com-eligibility.yml
source_heading: Eligibility
source_page: https://canuckeats.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Canuck Eats\naid: canuckeats-com\nurl: https://canuckeats.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - CA\n  excluded: []\n  text: Live nationwide, more added daily British Columbia Alberta Saskatchewan Manitoba Ontario Quebec Nova Scotia\n    New Brunswick Newfoundland & Labrador Prince Edward Island Yukon Northwest Territories\nentity_types:\n- type: individual\n  text: You must be at least 18 years of age (or the age of majority in your province of residence, whichever is\n    greater) to create an account or place an Order.\nrestricted_uses:\n- summary: Unlawful or fraudulent use\n  text:\
  \ Use the Platform for any unlawful purpose or in violation of any applicable laws or regulations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years of age (or the age of majority in your province of residence, whichever is\n    greater)\n"
source_yaml_url: https://artifacts.apis.io/canuckeats-com/eligibility/canuckeats-com-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Canuck Eats's own page on 2026-11-09.
synthetic: false
tags:
- Food Delivery
- Canada
- Price Comparison
- Restaurant
- Marketplace
---
