---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 13 years old to register on your own; younger children may register and use the Service only with the consent of a parent or legal guardian.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to register on your own
    value: '13'
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: New accounts require approval by an Admin or a Site Manager before access is granted.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: 4DReplay
provenance_date: '2026-11-09'
provider_name: 4DReplay
provider_slug: 4dreplay
slug: 4dreplay-eligibility
source_date: '2026-11-09'
source_filename: 4dreplay-eligibility.yml
source_heading: Eligibility
source_page: https://4dtrack.com/terms.html
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: 4DReplay\naid: 4dreplay\nurl: https://4dtrack.com/terms.html\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to register on your own; younger children may register and use the Service\n    only with the consent of a parent or legal guardian.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: New accounts require approval by an Admin or a Site Manager before access is granted.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to register\
  \ on your own\n"
source_yaml_url: https://artifacts.apis.io/4dreplay/eligibility/4dreplay-eligibility.yml
stated_fields:
- entity_types
- verification
- minimum_age
summary_line: 3 quoted statements, read from 4DReplay's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Video
- Sports
- Media
- Broadcasting
- Streaming
- OTT
- Artificial Intelligence
- Computer Vision
- Entertainment
---
