---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a minor, you must have the consent of a parent or other legal guardian to use the Service.
    type: individual
  - text: If you use the Service for the work of a company or other organization, please get any approval you need within that company or other legal entity first.
    type: business
  minimum_age:
    text: null
    value: null
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Registration requires confirming an email address we accept.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: CLUBS
provenance_date: '2026-11-09'
provider_name: CLUBS
provider_slug: clubs-place
slug: clubs-place-eligibility
source_date: '2026-11-09'
source_filename: clubs-place-eligibility.yml
source_heading: Eligibility
source_page: https://clubs.place/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CLUBS\naid: clubs-place\nurl: https://clubs.place/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a minor, you must have the consent of a parent or other legal guardian to use the Service.\n- type: business\n  text: If you use the Service for the work of a company or other organization, please get any approval you need\n    within that company or other legal entity first.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Registration requires confirming an email address\
  \ we accept.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/clubs-place/eligibility/clubs-place-eligibility.yml
stated_fields:
- entity_types
- verification
summary_line: 3 quoted statements, read from CLUBS's own page on 2026-11-09.
synthetic: false
tags:
- Company
- AI
- Model Context Protocol
- Productivity
- Notes
- Reporting
- Japan
---
