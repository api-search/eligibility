---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: MUTUALLY AGREED UPON BY THE ORGANIZATION IDENTIFIED THEREIN
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Criminal activity
    text: (h) further or promote any criminal activity or enterprise or provide instructional information about illegal activities
  - summary: HIPAA protected health information
    text: Until Customer has entered into a Business Associate Agreement with Broadly, neither Customer nor any of its Users shall send Protected Health Information to Broadly
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
name: Broadly
provenance_date: '2026-11-09'
provider_name: Broadly
provider_slug: broadly
slug: broadly-eligibility
source_date: '2026-11-09'
source_filename: broadly-eligibility.yml
source_heading: Eligibility
source_page: https://broadly.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Broadly\naid: broadly\nurl: https://broadly.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: MUTUALLY AGREED UPON BY THE ORGANIZATION IDENTIFIED THEREIN\nrestricted_uses:\n- summary: Criminal activity\n  text: (h) further or promote any criminal activity or enterprise or provide instructional information about illegal\n    activities\n- summary: HIPAA protected health information\n  text: Until Customer has entered into a Business Associate Agreement with Broadly, neither Customer nor any of\n    its Users shall send Protected\
  \ Health Information to Broadly\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/broadly/eligibility/broadly-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Broadly's own page on 2026-11-09.
synthetic: false
tags:
- AI Workforce
- Reputation Management
- Local SEO
- CRM
- Messaging
- Appointment Scheduling
- Marketing Automation
- Home Services
---
