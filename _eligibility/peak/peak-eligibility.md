---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Use of this Service is void where prohibited.
  entity_types:
  - text: By registering for an Account or otherwise using the Service, you represent that you are age 13 or older
    type: individual
  minimum_age:
    text: you represent that you are age 13 or older
    value: '13'
  restricted_uses:
  - summary: Non-commercial use only
    text: You shall use your Account only for non-commercial purposes.
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
name: Peak
provenance_date: '2026-11-10'
provider_name: Peak
provider_slug: peak
slug: peak-eligibility
source_date: '2026-11-10'
source_filename: peak-eligibility.yml
source_heading: Eligibility
source_page: https://www.synapticlabs.uk/termsofservice
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Peak\naid: peak\nurl: https://www.synapticlabs.uk/termsofservice\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Use of this Service is void where prohibited.\nentity_types:\n- type: individual\n  text: By registering for an Account or otherwise using the Service, you represent that you are age 13 or older\nrestricted_uses:\n- summary: Non-commercial use only\n  text: You shall use your Account only for non-commercial purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: you represent that you are age 13\
  \ or older\n"
source_yaml_url: https://artifacts.apis.io/peak/eligibility/peak-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Peak's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Consumer
- Brain Training
- Cognitive Training
- Mobile App
- Games
- Health and Fitness
- Education
---
