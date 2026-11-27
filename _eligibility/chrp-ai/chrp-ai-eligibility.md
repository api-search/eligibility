---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years of age to use the Service.
    type: individual
  minimum_age:
    text: You must be at least 13 years of age to use the Service.
    value: '13'
  restricted_uses:
  - summary: Not a medical device or diagnostic
    text: CHRP® IS NOT A MEDICAL DEVICE. The Service does not diagnose medical or psychological conditions
  - summary: No medical, employment or legal decisions
    text: EPI Score™ results should not be used as the basis for medical, psychiatric, employment, or legal decisions.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must create an account to use the Service.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CHRP
provenance_date: '2026-11-09'
provider_name: CHRP
provider_slug: chrp-ai
slug: chrp-ai-eligibility
source_date: '2026-11-09'
source_filename: chrp-ai-eligibility.yml
source_heading: Eligibility
source_page: https://chrp.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CHRP\naid: chrp-ai\nurl: https://chrp.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years of age to use the Service.\nrestricted_uses:\n- summary: Not a medical device or diagnostic\n  text: CHRP® IS NOT A MEDICAL DEVICE. The Service does not diagnose medical or psychological conditions\n- summary: No medical, employment or legal decisions\n  text: EPI Score™ results should not be used as the basis for medical, psychiatric, employment, or legal decisions.\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: You must create an account to use the Service.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years of age to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/chrp-ai/eligibility/chrp-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from CHRP's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Emotional Intelligence
- Team Performance
- Analytics
---
