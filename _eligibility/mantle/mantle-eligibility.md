---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: You may use the Services only if you are at least 18 years old, capable of forming a binding contract with Ten Key Labs
    type: individual
  minimum_age:
    text: You may use the Services only if you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: Activity violating law or sanctions
    text: Engage or assist in any activity that violates any law, statute, ordinance, regulation, or sanctions program
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
name: Mantle
provenance_date: '2026-11-10'
provider_name: Mantle
provider_slug: mantle
slug: mantle-eligibility
source_date: '2026-11-10'
source_filename: mantle-eligibility.yml
source_heading: Eligibility
source_page: https://withmantle.com/resources/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mantle\naid: mantle\nurl: https://withmantle.com/resources/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: you are not located in a country that is subject to a U.S. Government embargo\nentity_types:\n- type: individual\n  text: You may use the Services only if you are at least 18 years old, capable of forming a binding contract with\n    Ten Key Labs\nrestricted_uses:\n- summary: Activity violating law or sanctions\n  text: Engage or assist in any activity that violates any law, statute, ordinance, regulation, or sanctions program\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/mantle/eligibility/mantle-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Mantle's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Cap Table
- Equity Management
- Portfolio Management
- Alternative Assets
- Fintech
- Software-as-a-Service
- 409A Valuation
---
