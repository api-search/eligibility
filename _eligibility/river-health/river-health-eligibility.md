---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: For individuals purchasing a River Health Plan independently, not through an employer, a minimum commitment of 3 months is required.
    type: individual
  - text: For some members, your employer will cover your membership fees. In this case, River Health will not bill you for an annual or monthly membership.
    type: business
  minimum_age:
    text: You can only register to use River Health if you are at least 14 years of age.
    value: '14'
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
name: River Health
provenance_date: '2026-11-10'
provider_name: River Health
provider_slug: river-health
slug: river-health-eligibility
source_date: '2026-11-10'
source_filename: river-health-eligibility.yml
source_heading: Eligibility
source_page: https://river.health/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: River Health\naid: river-health\nurl: https://river.health/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: For individuals purchasing a River Health Plan independently, not through an employer, a minimum commitment\n    of 3 months is required.\n- type: business\n  text: For some members, your employer will cover your membership fees. In this case, River Health will not bill\n    you for an annual or monthly membership.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: '14'\n  text: You can only register to use River Health if you are at least 14 years of age.\n"
source_yaml_url: https://artifacts.apis.io/river-health/eligibility/river-health-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from River Health's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Primary Care
- Behavioral Health
- Mental Health
- Employee Benefits
- Digital Health
---
