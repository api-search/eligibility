---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you are over the age of thirteen (13) and have the power, authority or consent to enter into and perform your obligations under the Agreement
    type: individual
  minimum_age:
    text: you are over the age of thirteen (13)
    value: '13'
  restricted_uses:
  - summary: Export and sanctions compliance
    text: you are not located in, under the control of, or a national or resident of any restricted country or on any such list.
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
name: 2ULaundry
provenance_date: '2026-11-09'
provider_name: 2ULaundry
provider_slug: 2ulaundry
slug: 2ulaundry-eligibility
source_date: '2026-11-09'
source_filename: 2ulaundry-eligibility.yml
source_heading: Eligibility
source_page: https://www.2ulaundry.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 2ULaundry\naid: 2ulaundry\nurl: https://www.2ulaundry.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you are over the age of thirteen (13) and have the power, authority or consent to enter into and perform\n    your obligations under the Agreement\nrestricted_uses:\n- summary: Export and sanctions compliance\n  text: you are not located in, under the control of, or a national or resident of any restricted country or on\n    any such list.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: you are over the age of thirteen (13)\n"
source_yaml_url: https://artifacts.apis.io/2ulaundry/eligibility/2ulaundry-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from 2ULaundry's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Laundry
- Dry Cleaning
- Delivery
- Logistics
- Consumer Services
- On-Demand
---
