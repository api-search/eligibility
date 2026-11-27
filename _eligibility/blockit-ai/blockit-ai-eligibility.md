---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: This Section 17 applies to users of the Services within the United States.
  entity_types:
  - text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with Blockit
    type: individual
  minimum_age:
    text: You may use the Services only if you are 18 years or older
    value: '18'
  restricted_uses:
  - summary: No PHI, NPI, or regulated sensitive data
    text: Provide, transmit, or otherwise make available to the Services any (i) Protected Health Information (PHI) (as defined by the Health Insurance Portability and Accountability Act of 1996); (ii) Nonpublic Personal Information (NPI)
  verification:
    approval_required: null
    kyb: null
    kyc: true
    text: You may need to provide additional information to verify your identity before completing your Transaction
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Blockit AI
provenance_date: '2026-11-09'
provider_name: Blockit AI
provider_slug: blockit-ai
slug: blockit-ai-eligibility
source_date: '2026-11-09'
source_filename: blockit-ai-eligibility.yml
source_heading: Eligibility
source_page: https://www.blockit.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blockit AI\naid: blockit-ai\nurl: https://www.blockit.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: This Section 17 applies to users of the Services within the United States.\nentity_types:\n- type: individual\n  text: You may use the Services only if you are 18 years or older and capable of forming a binding contract with\n    Blockit\nrestricted_uses:\n- summary: No PHI, NPI, or regulated sensitive data\n  text: Provide, transmit, or otherwise make available to the Services any (i) Protected Health Information (PHI)\n    (as defined by the Health Insurance Portability\
  \ and Accountability Act of 1996); (ii) Nonpublic Personal Information\n    (NPI)\nverification:\n  kyc: true\n  kyb: null\n  approval_required: null\n  text: You may need to provide additional information to verify your identity before completing your Transaction\nminimum_age:\n  value: '18'\n  text: You may use the Services only if you are 18 years or older\n"
source_yaml_url: https://artifacts.apis.io/blockit-ai/eligibility/blockit-ai-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Blockit AI's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Scheduling
- Productivity
- Calendar
---
