---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if you are an employee, agent, or other representative of a company or an organization, “you”, “your”, and similar terms shall refer to such entity
    type: business
  minimum_age:
    text: You must be at least thirteen (13) years old to use the Service.
    value: '13'
  restricted_uses:
  - summary: Export restrictions
    text: You will comply with all relevant U.S. and foreign export and import laws in using the Service
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: Verification of information may be required prior to the completion or acknowledgment of setting up any Payment Method.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Baton Media
provenance_date: '2026-11-09'
provider_name: Baton Media
provider_slug: baton-media
slug: baton-media-eligibility
source_date: '2026-11-09'
source_filename: baton-media-eligibility.yml
source_heading: Eligibility
source_page: https://baton.media/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Baton Media\naid: baton-media\nurl: https://baton.media/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: if you are an employee, agent, or other representative of a company or an organization, “you”, “your”, and\n    similar terms shall refer to such entity\nrestricted_uses:\n- summary: Export restrictions\n  text: You will comply with all relevant U.S. and foreign export and import laws in using the Service\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: Verification of information may be\
  \ required prior to the completion or acknowledgment of setting up any\n    Payment Method.\nminimum_age:\n  value: '13'\n  text: You must be at least thirteen (13) years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/baton-media/eligibility/baton-media-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 4 quoted statements, read from Baton Media's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Music
- Music Collaboration
- Creator Economy
- Intellectual Property
- Marketplace
- Audio
- Media
---
