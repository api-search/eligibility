---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You may use the Services only if you are eighteen (18) years or older, are capable of forming a binding contract with Phil and are not barred from using the Services under applicable law.
    type: individual
  minimum_age:
    text: You may use the Services only if you are eighteen (18) years or older
    value: '18'
  restricted_uses:
  - summary: Controlled substance prescriptions
    text: You agree not to submit controlled substance prescriptions through the Services, except as expressly authorized by Phil in connection with specific programs or medications made available by Phil for which Phil has established applicable controls.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may need to provide additional information to verify your identity before completing your Order
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Phil
provenance_date: '2026-11-10'
provider_name: Phil
provider_slug: phil
slug: phil-eligibility
source_date: '2026-11-10'
source_filename: phil-eligibility.yml
source_heading: Eligibility
source_page: https://phil.us/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Phil\naid: phil\nurl: https://phil.us/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You may use the Services only if you are eighteen (18) years or older, are capable of forming a binding\n    contract with Phil and are not barred from using the Services under applicable law.\nrestricted_uses:\n- summary: Controlled substance prescriptions\n  text: You agree not to submit controlled substance prescriptions through the Services, except as expressly authorized\n    by Phil in connection with specific programs or medications\
  \ made available by Phil for which Phil has established\n    applicable controls.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Order\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are eighteen (18) years or older\n"
source_yaml_url: https://artifacts.apis.io/phil/eligibility/phil-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Phil's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Health Tech
- Pharmacy
- Direct-to-Patient
- Medication Access
- Digital Health
- Prescriptions
---
