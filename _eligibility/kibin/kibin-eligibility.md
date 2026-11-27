---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are between 13 and 18 (or the age of majority in your jurisdiction), you may use the Services only with the consent of a parent or legal guardian who agrees to these Terms on your behalf.
    type: individual
  minimum_age:
    text: The Services are not available to users under 13 years old.
    value: '13'
  restricted_uses:
  - summary: Commercial transcription, content generation, or resale
    text: (i) use the Services for commercial transcription, content generation, or resale
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
name: Kibin
provenance_date: '2026-11-09'
provider_name: Kibin
provider_slug: kibin
slug: kibin-eligibility
source_date: '2026-11-09'
source_filename: kibin-eligibility.yml
source_heading: Eligibility
source_page: https://kibin.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kibin\naid: kibin\nurl: https://kibin.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are between 13 and 18 (or the age of majority in your jurisdiction), you may use the Services only\n    with the consent of a parent or legal guardian who agrees to these Terms on your behalf.\nrestricted_uses:\n- summary: Commercial transcription, content generation, or resale\n  text: (i) use the Services for commercial transcription, content generation, or resale\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n\
  \  text: null\nminimum_age:\n  value: '13'\n  text: The Services are not available to users under 13 years old.\n"
source_yaml_url: https://artifacts.apis.io/kibin/eligibility/kibin-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Kibin's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Education
- EdTech
- Study Tools
- AI Study Assistant
- Academic Writing
- Essay Editing
- Flashcards
- Students
- Consumer App
---
