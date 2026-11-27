---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an individual, you are of legal age to enter into a binding contract
    type: individual
  - text: if you are registering on behalf of a legal entity, that you are authorized to enter into, and bind the entity to, these User Terms
    type: business
  minimum_age:
    text: if you are an individual, you are of legal age to enter into a binding contract
    value: null
  restricted_uses:
  - summary: Unlawful or fraudulent purposes
    text: You will not use the HONK Service for unlawful purposes, including but not limited to sending or storing any unlawful material or for fraudulent purposes
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: HONK is entitled at all times to verify the information that you have provided and to refuse the HONK Service for any reason or no reason.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Honk
provenance_date: '2026-11-09'
provider_name: Honk
provider_slug: honk
slug: honk-eligibility
source_date: '2026-11-09'
source_filename: honk-eligibility.yml
source_heading: Eligibility
source_page: https://www.honkforhelp.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Honk\naid: honk\nurl: https://www.honkforhelp.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if you are an individual, you are of legal age to enter into a binding contract\n- type: business\n  text: if you are registering on behalf of a legal entity, that you are authorized to enter into, and bind the\n    entity to, these User Terms\nrestricted_uses:\n- summary: Unlawful or fraudulent purposes\n  text: You will not use the HONK Service for unlawful purposes, including but not limited to sending or storing\n\
  \    any unlawful material or for fraudulent purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: HONK is entitled at all times to verify the information that you have provided and to refuse the HONK Service\n    for any reason or no reason.\nminimum_age:\n  value: null\n  text: if you are an individual, you are of legal age to enter into a binding contract\n"
source_yaml_url: https://artifacts.apis.io/honk/eligibility/honk-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Honk's own page on 2026-11-09.
synthetic: false
tags:
- Roadside Assistance
- Fleet Management
- Insurance Solutions
- Logistics Management
- Accident Management
- Reimbursement
- Specialized Vehicles
---
