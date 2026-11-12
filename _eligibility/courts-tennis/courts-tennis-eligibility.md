---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: To do that you must be 18 or older, and you sign in with a 4GRAND account.
    value: '18'
  restricted_uses:
  - summary: Player feature rules
    text: Do not use this to advertise, to contact people for anything but tennis, or to bother anyone.
  verification:
    approval_required: null
    kyb: null
    kyc: false
    text: We do not check who anyone is beyond their phone number.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Courts.tennis
provenance_date: '2026-11-09'
provider_name: Courts.tennis
provider_slug: courts-tennis
slug: courts-tennis-eligibility
source_date: '2026-11-09'
source_filename: courts-tennis-eligibility.yml
source_heading: Eligibility
source_page: https://www.courts.tennis/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Courts.tennis\naid: courts-tennis\nurl: https://www.courts.tennis/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Player feature rules\n  text: Do not use this to advertise, to contact people for anything but tennis, or to bother anyone.\nverification:\n  kyc: false\n  kyb: null\n  approval_required: null\n  text: We do not check who anyone is beyond their phone number.\nminimum_age:\n  value: '18'\n  text: To do that you must be 18 or older, and you sign in with a 4GRAND account.\n"
source_yaml_url: https://artifacts.apis.io/courts-tennis/eligibility/courts-tennis-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Courts.tennis's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Tennis
- Sports
- Sports Facilities
- Directories
- Open Data
- Model Context Protocol
- Travel
---
