---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are at least 18 years of age or the age of majority in your jurisdiction, capable of forming a binding contract with Fondue
    type: individual
  minimum_age:
    text: you are at least 18 years of age or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Card cash restriction
    text: Cards cannot be redeemed for cash or used to obtain cash
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
name: Fondue
provenance_date: '2026-11-09'
provider_name: Fondue
provider_slug: fondue
slug: fondue-eligibility
source_date: '2026-11-09'
source_filename: fondue-eligibility.yml
source_heading: Eligibility
source_page: https://www.getfondue.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Fondue\naid: fondue\nurl: https://www.getfondue.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are at least 18 years of age or the age of majority in your jurisdiction, capable of forming a binding\n    contract with Fondue\nrestricted_uses:\n- summary: Card cash restriction\n  text: Cards cannot be redeemed for cash or used to obtain cash\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years of age or the age of majority\
  \ in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/fondue/eligibility/fondue-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Fondue's own page on 2026-11-09.
synthetic: false
tags:
- Company
---
