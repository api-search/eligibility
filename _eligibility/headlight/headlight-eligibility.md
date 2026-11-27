---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Service for use only by persons located in the United States.
  entity_types:
  - text: You are age 18 or over or, if you are under 18 years old, you have the express consent of your parent or guardian
    type: individual
  minimum_age:
    text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.
    value: '13'
  restricted_uses:
  - summary: Not for emergencies
    text: THE SERVICE IS NOT INTENDED FOR USE IN A MEDICAL EMERGENCY.
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
name: Headlight
provenance_date: '2026-11-09'
provider_name: Headlight
provider_slug: headlight
slug: headlight-eligibility
source_date: '2026-11-09'
source_filename: headlight-eligibility.yml
source_heading: Eligibility
source_page: https://headlight.health/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Headlight\naid: headlight\nurl: https://headlight.health/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Service for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: You are age 18 or over or, if you are under 18 years old, you have the express consent of your parent or\n    guardian\nrestricted_uses:\n- summary: Not for emergencies\n  text: THE SERVICE IS NOT INTENDED FOR USE IN A MEDICAL EMERGENCY.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\n\
  minimum_age:\n  value: '13'\n  text: If you are under 13 years of age, you are not authorized to use the Service, with or without registering.\n"
source_yaml_url: https://artifacts.apis.io/headlight/eligibility/headlight-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Headlight's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health Tech
- Mental Health
- Telehealth
- Teletherapy
- Psychiatry
- Behavioral Health
- Healthcare
---
