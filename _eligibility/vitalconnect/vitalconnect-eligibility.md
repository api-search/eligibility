---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are an individual who is at least 18 years old
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Not for medical emergencies or critical care
    text: THE SERVICE MUST NOT BE USED IN MEDICAL EMERGENCIES OR BY CRITICAL CARE PATIENTS.
  - summary: Not while driving or operating machinery
    text: use the Service during any activity that may distract you from safely doing other activities; for example, using the Service while driving or operating machinery
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To access most features of the Service, your health care provider must register you for an account.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: VitalConnect
provenance_date: '2026-11-10'
provider_name: VitalConnect
provider_slug: vitalconnect
slug: vitalconnect-eligibility
source_date: '2026-11-10'
source_filename: vitalconnect-eligibility.yml
source_heading: Eligibility
source_page: https://vitalconnect.com/eula/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: VitalConnect\naid: vitalconnect\nurl: https://vitalconnect.com/eula/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are an individual who is at least 18 years old\nrestricted_uses:\n- summary: Not for medical emergencies or critical care\n  text: THE SERVICE MUST NOT BE USED IN MEDICAL EMERGENCIES OR BY CRITICAL CARE PATIENTS.\n- summary: Not while driving or operating machinery\n  text: use the Service during any activity that may distract you from safely doing other activities; for example,\n    using the Service while driving\
  \ or operating machinery\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To access most features of the Service, your health care provider must register you for an account.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/vitalconnect/eligibility/vitalconnect-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from VitalConnect's own page on 2026-11-10.
synthetic: false
tags:
- Health
- Healthcare
- Medical Devices
- Remote Patient Monitoring
- Cardiac Monitoring
- Biosensors
- Wearables
- Telehealth
- Clinical Trials
- Webhook
---
