---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Individuals or professionals
    type: individual
  minimum_age:
    text: Over the age of 16 (sixteen) at the time of the request to create the Account.
    value: '16'
  restricted_uses:
  - summary: Lawful and good-faith use only
    text: In general, the User undertakes to use the Application in compliance with the public policy regulations, good morals and the legal and regulatory provisions in force.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: An email is then sent by LITHIUM to the User at the given email address indicating a code to complete the registration.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Kosmik
provenance_date: '2026-11-09'
provider_name: Kosmik
provider_slug: kosmik
slug: kosmik-eligibility
source_date: '2026-11-09'
source_filename: kosmik-eligibility.yml
source_heading: Eligibility
source_page: https://www.kosmik.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kosmik\naid: kosmik\nurl: https://www.kosmik.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Individuals or professionals\nrestricted_uses:\n- summary: Lawful and good-faith use only\n  text: In general, the User undertakes to use the Application in compliance with the public policy regulations,\n    good morals and the legal and regulatory provisions in force.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: An email is then sent by LITHIUM to the User at the given email address indicating a code\
  \ to complete the\n    registration.\nminimum_age:\n  value: '16'\n  text: Over the age of 16 (sixteen) at the time of the request to create the Account.\n"
source_yaml_url: https://artifacts.apis.io/kosmik/eligibility/kosmik-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Kosmik's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Productivity
- Visual Collaboration
- Infinite Canvas
- Moodboard
- Personal Knowledge Management
- Artificial Intelligence
- Local-First
- Sunset
- Defunct
---
