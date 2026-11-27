---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Website is available only to individuals who are at least 13 years old.
    type: individual
  - text: For "CircuitLab Pro" and "CircuitLab Enterprise" users, commercial use is explicitly allowed.
    type: business
  minimum_age:
    text: The Website is available only to individuals who are at least 13 years old.
    value: '13'
  restricted_uses:
  - summary: Safety-critical applications
    text: The use of CircuitLab schematics or simulations for safety-critical applications, such as life support, medical devices, nuclear control systems, or any system where device failure could reasonably be expected to cause personal injury or death, is not authorized under this Terms of Service.
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
name: CircuitLab
provenance_date: '2026-11-09'
provider_name: CircuitLab
provider_slug: circuitlab
slug: circuitlab-eligibility
source_date: '2026-11-09'
source_filename: circuitlab-eligibility.yml
source_heading: Eligibility
source_page: https://www.circuitlab.com/legal/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CircuitLab\naid: circuitlab\nurl: https://www.circuitlab.com/legal/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Website is available only to individuals who are at least 13 years old.\n- type: business\n  text: For \"CircuitLab Pro\" and \"CircuitLab Enterprise\" users, commercial use is explicitly allowed.\nrestricted_uses:\n- summary: Safety-critical applications\n  text: The use of CircuitLab schematics or simulations for safety-critical applications, such as life support,\n    medical devices, nuclear control systems, or\
  \ any system where device failure could reasonably be expected to\n    cause personal injury or death, is not authorized under this Terms of Service.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Website is available only to individuals who are at least 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/circuitlab/eligibility/circuitlab-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from CircuitLab's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Electronics
- Circuit Simulation
- Schematic Capture
- EDA
- Simulation
- Engineering
- Education
---
