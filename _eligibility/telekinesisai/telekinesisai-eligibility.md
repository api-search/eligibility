---
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Commercial use requires age 18 or corporate authority.
    type: business
  - text: 'Users must provide: First name Last name Email Role (student, hobbyist, researcher, employee)'
    type: individual
  minimum_age:
    text: 'Minimum age: 16 (GDPR Art. 8).'
    value: '16'
  restricted_uses:
  - summary: Military applications
    text: Military applications
  - summary: Biometric identification
    text: Biometric identification
  - summary: High-risk surveillance
    text: High-risk surveillance
  - summary: Safety-critical control without redundancy
    text: Safety-critical control without redundancy
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
name: Telekinesis.ai
provenance_date: '2026-11-10'
provider_name: Telekinesis.ai
provider_slug: telekinesisai
slug: telekinesisai-eligibility
source_date: '2026-11-10'
source_filename: telekinesisai-eligibility.yml
source_heading: Eligibility
source_page: https://docs.telekinesis.ai/legal/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Telekinesis.ai\naid: telekinesisai\nurl: https://docs.telekinesis.ai/legal/terms.html\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: Commercial use requires age 18 or corporate authority.\n- type: individual\n  text: 'Users must provide: First name Last name Email Role (student, hobbyist, researcher, employee)'\nrestricted_uses:\n- summary: Military applications\n  text: Military applications\n- summary: Biometric identification\n  text: Biometric identification\n- summary: High-risk surveillance\n  text: High-risk surveillance\n- summary:\
  \ Safety-critical control without redundancy\n  text: Safety-critical control without redundancy\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: 'Minimum age: 16 (GDPR Art. 8).'\n"
source_yaml_url: https://artifacts.apis.io/telekinesisai/eligibility/telekinesisai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 7 quoted statements, read from Telekinesis.ai's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Robotics
- Computer Vision
- Physical AI
- Industrial Automation
- Manufacturing Automation
- 6D Pose Estimation
- Motion Planning
- Reinforcement Learning
- Python SDK
- Embodied Intelligence
- Agents
---
