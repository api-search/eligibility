---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: PawpRx is offered in select states, availability is subject to change.
  entity_types:
  - text: You may use the Services only if you are (i) 18 years or older and capable of forming a legal binding contract with Pawp
    type: individual
  minimum_age:
    text: You may use the Services only if you are (i) 18 years or older and capable of forming a legal binding contract with Pawp
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials provided by Pawp hereunder, to any country for which the United States or any other relevant jurisdiction requires any export license
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
name: Pawp
provenance_date: '2026-11-10'
provider_name: Pawp
provider_slug: pawp
slug: pawp-eligibility
source_date: '2026-11-10'
source_filename: pawp-eligibility.yml
source_heading: Eligibility
source_page: https://pawp.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pawp\naid: pawp\nurl: https://pawp.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: PawpRx is offered in select states, availability is subject to change.\nentity_types:\n- type: individual\n  text: You may use the Services only if you are (i) 18 years or older and capable of forming a legal binding contract\n    with Pawp\nrestricted_uses:\n- summary: Export restrictions\n  text: you will not export or re-export, directly or indirectly, the Services and/or other information or materials\n    provided by Pawp hereunder, to any country for which the United States or any other\
  \ relevant jurisdiction requires\n    any export license\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are (i) 18 years or older and capable of forming a legal binding contract\n    with Pawp\n"
source_yaml_url: https://artifacts.apis.io/pawp/eligibility/pawp-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pawp's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Pets
- Veterinary
- Telehealth
- Health
- Insurance
---
