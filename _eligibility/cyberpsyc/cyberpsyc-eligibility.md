---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Programs are designed for adult users 18+. Users aged 13-17 may access certain portions of the platform only.
    type: individual
  minimum_age:
    text: The Programs are designed for adult users 18+. Users aged 13-17 may access certain portions of the platform only. Users under age 13 years are prohibited from use.
    value: '18'
  restricted_uses:
  - summary: Under-13 use prohibited
    text: Users under age 13 years are prohibited from use.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use the Services, you must create an account on the Website or app including providing your name and basic contact details and choosing a password to log in and out of your profile.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Cyberpsyc
provenance_date: '2026-11-09'
provider_name: Cyberpsyc
provider_slug: cyberpsyc
slug: cyberpsyc-eligibility
source_date: '2026-11-09'
source_filename: cyberpsyc-eligibility.yml
source_heading: Eligibility
source_page: https://app.welltrack-boost.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Cyberpsyc\naid: cyberpsyc\nurl: https://app.welltrack-boost.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Programs are designed for adult users 18+. Users aged 13-17 may access certain portions of the platform\n    only.\nrestricted_uses:\n- summary: Under-13 use prohibited\n  text: Users under age 13 years are prohibited from use.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use the Services, you must create an account on the Website or app including providing your\
  \ name and\n    basic contact details and choosing a password to log in and out of your profile.\nminimum_age:\n  value: '18'\n  text: The Programs are designed for adult users 18+. Users aged 13-17 may access certain portions of the platform\n    only. Users under age 13 years are prohibited from use.\n"
source_yaml_url: https://artifacts.apis.io/cyberpsyc/eligibility/cyberpsyc-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Cyberpsyc's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mental Health
- Behavioral Health
- Wellness
- Digital Therapeutics
- CBT
- Healthcare
- Higher Education
- SSO
- Identity Federation
---
