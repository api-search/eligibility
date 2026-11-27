---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are under 18 years old, you may use the Services only with the approval of your parent or guardian, with the exception of Atlas which is not available to users under 18 years of age.
    type: individual
  minimum_age:
    text: with the exception of Atlas which is not available to users under 18 years of age
    value: '18'
  restricted_uses:
  - summary: Not medical advice
    text: The Services are not designed to diagnose, treat, mitigate or cure any disease, physical or mental health condition and are not a substitute for medical advice
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
name: The Mind Company
provenance_date: '2026-11-10'
provider_name: The Mind Company
provider_slug: themindcompany
slug: themindcompany-eligibility
source_date: '2026-11-10'
source_filename: themindcompany-eligibility.yml
source_heading: Eligibility
source_page: https://themindcompany.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: The Mind Company\naid: themindcompany\nurl: https://themindcompany.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are under 18 years old, you may use the Services only with the approval of your parent or guardian,\n    with the exception of Atlas which is not available to users under 18 years of age.\nrestricted_uses:\n- summary: Not medical advice\n  text: The Services are not designed to diagnose, treat, mitigate or cure any disease, physical or mental health\n    condition and\
  \ are not a substitute for medical advice\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: with the exception of Atlas which is not available to users under 18 years of age\n"
source_yaml_url: https://artifacts.apis.io/themindcompany/eligibility/themindcompany-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from The Mind Company's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mental Health
- Wellness
- Cognitive Training
- Meditation
- Consumer App
- Mobile
- EdTech
---
