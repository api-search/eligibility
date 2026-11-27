---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Access to Daleela features depends on age. Period Tracker, AI assistant, and general educational programs are available to users aged 16 and older.
    type: individual
  minimum_age:
    text: Period Tracker, AI assistant, and general educational programs are available to users aged 16 and older.
    value: '16'
  restricted_uses:
  - summary: Medical consultations age limit
    text: Medical consultations are available only to users aged 18 and older.
  - summary: Sexual health programs age limit
    text: Sexual health educational programs are available to users aged 21 and older.
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
name: Daleela
provenance_date: '2026-11-09'
provider_name: Daleela
provider_slug: daleela
slug: daleela-eligibility
source_date: '2026-11-09'
source_filename: daleela-eligibility.yml
source_heading: Eligibility
source_page: https://motherbeing.com/en/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Daleela\naid: daleela\nurl: https://motherbeing.com/en/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Access to Daleela features depends on age. Period Tracker, AI assistant, and general educational programs\n    are available to users aged 16 and older.\nrestricted_uses:\n- summary: Medical consultations age limit\n  text: Medical consultations are available only to users aged 18 and older.\n- summary: Sexual health programs age limit\n  text: Sexual health educational programs are available to users aged 21 and older.\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: Period Tracker, AI assistant, and general educational programs are available to users aged 16 and older.\n"
source_yaml_url: https://artifacts.apis.io/daleela/eligibility/daleela-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Daleela's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Women's Health
- Femtech
- Health
- Telehealth
- Mobile App
- AI Assistant
- MENA
---
