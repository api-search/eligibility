---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
  entity_types:
  - text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
    type: individual
  - text: If you use the Services on behalf of a company or other entity, then "you" includes you and that entity
    type: business
  minimum_age:
    text: You must be 18 years of age or older and reside in the United States or any of its territories to use the Services.
    value: '18'
  restricted_uses:
  - summary: Medical emergencies
    text: 'NOT for emergencies of any sort: call 911 for any medical emergency.'
  - summary: Mental health crises
    text: NOT for mental health crises, thoughts of suicide or self-harm, or thoughts of violence.
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
name: Doctronic
provenance_date: '2026-11-09'
provider_name: Doctronic
provider_slug: doctronic
slug: doctronic-eligibility
source_date: '2026-11-09'
source_filename: doctronic-eligibility.yml
source_heading: Eligibility
source_page: https://www.doctronic.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Doctronic\naid: doctronic\nurl: https://www.doctronic.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served:\n  - US\n  excluded: []\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\nentity_types:\n- type: individual\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\n- type: business\n  text: If you use the Services on behalf of a company or other entity, then \"you\" includes you and that entity\nrestricted_uses:\n\
  - summary: Medical emergencies\n  text: 'NOT for emergencies of any sort: call 911 for any medical emergency.'\n- summary: Mental health crises\n  text: NOT for mental health crises, thoughts of suicide or self-harm, or thoughts of violence.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be 18 years of age or older and reside in the United States or any of its territories to use the\n    Services.\n"
source_yaml_url: https://artifacts.apis.io/doctronic/eligibility/doctronic-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Doctronic's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Health
- Telehealth
- Artificial Intelligence
- Healthcare
- Digital Health
- Consumer
---
