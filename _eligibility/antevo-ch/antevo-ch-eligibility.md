---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years of age (or the minimum age of digital consent in your country of residence, if lower) to register for an account and consent to data processing under the GDPR.
    type: individual
  minimum_age:
    text: You must be at least 16 years of age (or the minimum age of digital consent in your country of residence, if lower) to register for an account and consent to data processing under the GDPR.
    value: '16'
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
name: antevo-ch
provenance_date: '2026-11-09'
provider_name: antevo-ch
provider_slug: antevo-ch
slug: antevo-ch-eligibility
source_date: '2026-11-09'
source_filename: antevo-ch-eligibility.yml
source_heading: Eligibility
source_page: https://antevo.ch/policies/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: antevo-ch\naid: antevo-ch\nurl: https://antevo.ch/policies/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years of age (or the minimum age of digital consent in your country of residence,\n    if lower) to register for an account and consent to data processing under the GDPR.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years of age (or the minimum age of digital consent in your\
  \ country of residence,\n    if lower) to register for an account and consent to data processing under the GDPR.\n"
source_yaml_url: https://artifacts.apis.io/antevo-ch/eligibility/antevo-ch-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from antevo-ch's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Wealth
- Data Integration
- AI Assistant
- Swiss
---
