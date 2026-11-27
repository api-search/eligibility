---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Country refers to the United States.
  entity_types:
  - text: You represent that you are over the age of 18.
    type: individual
  minimum_age:
    text: The Company does not permit those under 18 to use the Service.
    value: '18'
  restricted_uses:
  - summary: Health information not a substitute for medical advice
    text: THE FITON SERVICE OFFERS HEALTH AND FITNESS INFORMATION AND IS DESIGNED FOR EDUCATIONAL AND ENTERTAINMENT PURPOSES ONLY.
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
name: FitOn
provenance_date: '2026-11-09'
provider_name: FitOn
provider_slug: fiton
slug: fiton-eligibility
source_date: '2026-11-09'
source_filename: fiton-eligibility.yml
source_heading: Eligibility
source_page: https://fitonapp.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FitOn\naid: fiton\nurl: https://fitonapp.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Country refers to the United States.\nentity_types:\n- type: individual\n  text: You represent that you are over the age of 18.\nrestricted_uses:\n- summary: Health information not a substitute for medical advice\n  text: THE FITON SERVICE OFFERS HEALTH AND FITNESS INFORMATION AND IS DESIGNED FOR EDUCATIONAL AND ENTERTAINMENT\n    PURPOSES ONLY.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Company does not\
  \ permit those under 18 to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/fiton/eligibility/fiton-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from FitOn's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Fitness
- Wellness
- Meditation
- Nutrition
- Consumer
- Mobile App
- Health and Fitness
---
