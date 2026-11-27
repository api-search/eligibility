---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Services are directed to adults in the United States and are not intended for individuals under the age of eighteen.
  entity_types:
  - text: The Services are primarily designed for business use.
    type: business
  - text: If you are an individual using the Services for non-commercial purposes
    type: individual
  minimum_age:
    text: the Services are directed to adults in the United States and are not intended for individuals under the age of eighteen.
    value: '18'
  restricted_uses:
  - summary: Sensitive information
    text: YOU AGREE NOT TO USE THE SERVICES TO COLLECT, MANAGE OR PROCESS SENSITIVE INFORMATION.
  - summary: Time-critical or mission-critical functions
    text: (vii) use the Services in connection with any of your time-critical or mission-critical functions.
  - summary: Weapons and prohibited purposes
    text: You also agree that you will not use the Services for any purposes prohibited by United States law, including, without limitation, the development, design, manufacture or production of nuclear, missiles, or chemical or biological weapons.
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
name: Day.ai
provenance_date: '2026-11-09'
provider_name: Day.ai
provider_slug: dayai
slug: dayai-eligibility
source_date: '2026-11-09'
source_filename: dayai-eligibility.yml
source_heading: Eligibility
source_page: https://day.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Day.ai\naid: dayai\nurl: https://day.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Services are directed to adults in the United States and are not intended for individuals under the\n    age of eighteen.\nentity_types:\n- type: business\n  text: The Services are primarily designed for business use.\n- type: individual\n  text: If you are an individual using the Services for non-commercial purposes\nrestricted_uses:\n- summary: Sensitive information\n  text: YOU AGREE NOT TO USE THE SERVICES TO COLLECT, MANAGE OR PROCESS SENSITIVE INFORMATION.\n\
  - summary: Time-critical or mission-critical functions\n  text: (vii) use the Services in connection with any of your time-critical or mission-critical functions.\n- summary: Weapons and prohibited purposes\n  text: You also agree that you will not use the Services for any purposes prohibited by United States law, including,\n    without limitation, the development, design, manufacture or production of nuclear, missiles, or chemical or\n    biological weapons.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: the Services are directed to adults in the United States and are not intended for individuals under the\n    age of eighteen.\n"
source_yaml_url: https://artifacts.apis.io/dayai/eligibility/dayai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Day.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Automation
- Enterprise
- Productivity
- Platform
---
