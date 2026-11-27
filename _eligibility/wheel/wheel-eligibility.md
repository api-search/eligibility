---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: the Services in the United States
  entity_types:
  - text: binding contract between you, an individual user
    type: individual
  minimum_age:
    text: You are at least eighteen (18) years of age
    value: '18'
  restricted_uses:
  - summary: No Workers' Compensation care
    text: Wheel does not treat patients presenting with issues or injuries related to Workers’ Compensation
  - summary: No Medicare-covered care
    text: you agree that you will not use the Services for an issue or injury that you anticipate or expect to be covered by Medicare.
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
name: Wheel
provenance_date: '2026-11-10'
provider_name: Wheel
provider_slug: wheel
slug: wheel-eligibility
source_date: '2026-11-10'
source_filename: wheel-eligibility.yml
source_heading: Eligibility
source_page: https://www.wheel.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wheel\naid: wheel\nurl: https://www.wheel.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: the Services in the United States\nentity_types:\n- type: individual\n  text: binding contract between you, an individual user\nrestricted_uses:\n- summary: No Workers' Compensation care\n  text: Wheel does not treat patients presenting with issues or injuries related to Workers’ Compensation\n- summary: No Medicare-covered care\n  text: you agree that you will not use the Services for an issue or injury that you anticipate or expect to be\n    covered by Medicare.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are at least eighteen (18) years of age\n"
source_yaml_url: https://artifacts.apis.io/wheel/eligibility/wheel-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Wheel's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Virtual Care
- Digital Health
- Clinician Network
- Care Enablement
- HIPAA
---
