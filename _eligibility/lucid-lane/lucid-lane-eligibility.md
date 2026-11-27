---
claim_count: 6
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: This site and application is intended for and applicable only for residents of the United States, age 18 or older.
  entity_types:
  - text: This site and application is intended for and applicable only for residents of the United States, age 18 or older.
    type: individual
  minimum_age:
    text: age 18 or older
    value: '18'
  restricted_uses:
  - summary: Not for emergencies
    text: DO NOT USE THIS SERVICE FOR EMERGENCY MEDICAL NEEDS.
  - summary: No provider-patient relationship or medical advice
    text: WE EXPLICITLY DISCLAIM THE CREATION OF A PROVIDER-PATIENT AND/OR THERAPIST-PATIENT RELATIONSHIP WITH YOU.
  - summary: Client data only in approved systems
    text: The Provider shall use Client Information solely for the purpose of providing services
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
name: Lucid Lane
provenance_date: '2026-11-09'
provider_name: Lucid Lane
provider_slug: lucid-lane
slug: lucid-lane-eligibility
source_date: '2026-11-09'
source_filename: lucid-lane-eligibility.yml
source_heading: Eligibility
source_page: https://www.skylerhealth.com/tou
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lucid Lane\naid: lucid-lane\nurl: https://www.skylerhealth.com/tou\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: This site and application is intended for and applicable only for residents of the United States, age 18\n    or older.\nentity_types:\n- type: individual\n  text: This site and application is intended for and applicable only for residents of the United States, age 18\n    or older.\nrestricted_uses:\n- summary: Not for emergencies\n  text: DO NOT USE THIS SERVICE FOR EMERGENCY MEDICAL NEEDS.\n- summary: No provider-patient relationship or medical advice\n  text:\
  \ WE EXPLICITLY DISCLAIM THE CREATION OF A PROVIDER-PATIENT AND/OR THERAPIST-PATIENT RELATIONSHIP WITH YOU.\n- summary: Client data only in approved systems\n  text: The Provider shall use Client Information solely for the purpose of providing services\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: age 18 or older\n"
source_yaml_url: https://artifacts.apis.io/lucid-lane/eligibility/lucid-lane-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 6 quoted statements, read from Lucid Lane's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Healthcare
- Telehealth
- Mental Health
- Behavioral Health
- Digital Therapeutics
- Wellness
- Teletherapy
- Startups
---
