---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: Services are intended for end use in the United States and are not labeled or intended for international distribution.
  entity_types:
  - text: you only may use our Sites and our Content for your personal use as an individual.
    type: individual
  minimum_age:
    text: YOU MUST BE AT LEAST EIGHTEEN (18) TO ACCESS AND USE OUR SITES.
    value: '18'
  restricted_uses:
  - summary: Not for urgent or emergency use
    text: Teletherapy services are not intended for and should not be used for urgent or emergency situations.
  - summary: AI services not for emergencies
    text: Our AI-supported Services are not intended for use in emergency or crisis situations.
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
name: Sondermind
provenance_date: '2026-11-10'
provider_name: Sondermind
provider_slug: sondermind
slug: sondermind-eligibility
source_date: '2026-11-10'
source_filename: sondermind-eligibility.yml
source_heading: Eligibility
source_page: https://privacy.sondermind.com/policies/en/?name=terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sondermind\naid: sondermind\nurl: https://privacy.sondermind.com/policies/en/?name=terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: Services are intended for end use in the United States and are not labeled or intended for international\n    distribution.\nentity_types:\n- type: individual\n  text: you only may use our Sites and our Content for your personal use as an individual.\nrestricted_uses:\n- summary: Not for urgent or emergency use\n  text: Teletherapy services are not intended for and should not be used for urgent or emergency situations.\n\
  - summary: AI services not for emergencies\n  text: Our AI-supported Services are not intended for use in emergency or crisis situations.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: YOU MUST BE AT LEAST EIGHTEEN (18) TO ACCESS AND USE OUR SITES.\n"
source_yaml_url: https://artifacts.apis.io/sondermind/eligibility/sondermind-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Sondermind's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mental Health
- Healthcare
- Telehealth
- Therapy
- Psychiatry
- Behavioral Health
- Digital Health
- HIPAA
---
