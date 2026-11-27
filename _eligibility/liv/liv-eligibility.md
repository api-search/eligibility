---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: As an individual using the Services for non-commercial purposes
    type: individual
  minimum_age:
    text: If you’re under 18, make sure your parent or legal guardian reads this too.
    value: '18'
  restricted_uses:
  - summary: Export restrictions
    text: You may not use or otherwise export or re-export the LIV Software except as authorized by United States law and the laws of the jurisdiction in which the LIV Software was obtained.
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
name: LIV
provenance_date: '2026-11-09'
provider_name: LIV
provider_slug: liv
slug: liv-eligibility
source_date: '2026-11-09'
source_filename: liv-eligibility.yml
source_heading: Eligibility
source_page: https://liv.tv/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: LIV\naid: liv\nurl: https://liv.tv/legal/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: As an individual using the Services for non-commercial purposes\nrestricted_uses:\n- summary: Export restrictions\n  text: You may not use or otherwise export or re-export the LIV Software except as authorized by United States\n    law and the laws of the jurisdiction in which the LIV Software was obtained.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If\
  \ you’re under 18, make sure your parent or legal guardian reads this too.\n"
source_yaml_url: https://artifacts.apis.io/liv/eligibility/liv-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from LIV's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Extended Reality
- Virtual Reality
- Mixed Reality
- Video Capture
- Live Streaming
- Game Engine SDK
- Unity
- Unreal Engine
- Meta Quest
---
