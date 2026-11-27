---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You are 18 years old or older to be able to receive the services in the Labayh App
    type: individual
  minimum_age:
    text: You are 18 years old or older to be able to receive the services in the Labayh App
    value: '18'
  restricted_uses:
  - summary: Medications for minors
    text: Medications are not dispensed through the application for individuals under 18 years old without parental consent.
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
name: Labayh
provenance_date: '2026-11-09'
provider_name: Labayh
provider_slug: labayh
slug: labayh-eligibility
source_date: '2026-11-09'
source_filename: labayh-eligibility.yml
source_heading: Eligibility
source_page: https://labayh.net/en/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Labayh\naid: labayh\nurl: https://labayh.net/en/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You are 18 years old or older to be able to receive the services in the Labayh App\nrestricted_uses:\n- summary: Medications for minors\n  text: Medications are not dispensed through the application for individuals under 18 years old without parental\n    consent.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You are 18 years old or older to be able\
  \ to receive the services in the Labayh App\n"
source_yaml_url: https://artifacts.apis.io/labayh/eligibility/labayh-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Labayh's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Mental Health
- Healthcare
- Telehealth
- Therapy
- Wellbeing
- Saudi Arabia
- Middle East
- Arabic
---
