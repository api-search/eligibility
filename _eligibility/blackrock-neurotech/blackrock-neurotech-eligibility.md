---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: This Website is intended for users who are at least 18 years old.
    type: individual
  - text: a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: This Website is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Personal, non-commercial use only
    text: The Website is offered to you for your personal and non-commercial purposes only
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
name: Blackrock Neurotech
provenance_date: '2026-11-09'
provider_name: Blackrock Neurotech
provider_slug: blackrock-neurotech
slug: blackrock-neurotech-eligibility
source_date: '2026-11-09'
source_filename: blackrock-neurotech-eligibility.yml
source_heading: Eligibility
source_page: https://blackrockneurotech.com/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blackrock Neurotech\naid: blackrock-neurotech\nurl: https://blackrockneurotech.com/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: This Website is intended for users who are at least 18 years old.\n- type: business\n  text: a legally binding agreement made between you, whether personally or on behalf of an entity\nrestricted_uses:\n- summary: Personal, non-commercial use only\n  text: The Website is offered to you for your personal and non-commercial purposes only\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '18'\n  text: This Website is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/blackrock-neurotech/eligibility/blackrock-neurotech-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Blackrock Neurotech's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Neurotechnology
- Brain-Computer Interface
- Medical Devices
- Neuroscience
- Research Instrumentation
- Implantable Devices
- Health Tech
- Assistive Technology
- Signal Processing
---
