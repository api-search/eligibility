---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may only access the Services (or make API Clients available to users) within an available region. You may use only Paid Services when making API Clients available to users in the European Economic Area, Switzerland, or the United Kingdom.
  entity_types:
  - text: Use of Google AI Studio and Gemini API is for developers building with Google AI models for professional or business purposes, not for consumer use.
    type: developer
  minimum_age:
    text: You must be 18 years of age or older to use the APIs.
    value: '18'
  restricted_uses:
  - summary: Clinical and medical use
    text: You may not use the Services in clinical practice, to provide medical advice, or in any manner that is overseen by or requires clearance or approval from a medical device regulatory agency.
  - summary: Safety-critical robotics use
    text: 'to not use the Robotics Models for safety-critical applications or work, such as in the following settings: (i) healthcare, (ii) transportation, or (iii) other areas where safety protocols are vital'
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
name: DeepMind
provenance_date: '2026-11-09'
provider_name: DeepMind
provider_slug: deepmind
slug: deepmind-eligibility
source_date: '2026-11-09'
source_filename: deepmind-eligibility.yml
source_heading: Eligibility
source_page: https://aistudio.google.com/docs/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: DeepMind\naid: deepmind\nurl: https://aistudio.google.com/docs/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may only access the Services (or make API Clients available to users) within an available region. You\n    may use only Paid Services when making API Clients available to users in the European Economic Area, Switzerland,\n    or the United Kingdom.\nentity_types:\n- type: developer\n  text: Use of Google AI Studio and Gemini API is for developers building with Google AI models for professional\n    or business purposes, not for consumer use.\nrestricted_uses:\n\
  - summary: Clinical and medical use\n  text: You may not use the Services in clinical practice, to provide medical advice, or in any manner that is overseen\n    by or requires clearance or approval from a medical device regulatory agency.\n- summary: Safety-critical robotics use\n  text: 'to not use the Robotics Models for safety-critical applications or work, such as in the following settings:\n    (i) healthcare, (ii) transportation, or (iii) other areas where safety protocols are vital'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older to use the APIs.\n"
source_yaml_url: https://artifacts.apis.io/deepmind/eligibility/deepmind-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from DeepMind's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Machine Learning
- Foundation Models
- LLM
- Research
- Robotics
- Developer Tools
---
