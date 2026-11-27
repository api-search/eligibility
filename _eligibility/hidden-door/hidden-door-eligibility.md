---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You must be at least 13 years old to use the Services.
    value: '13'
  restricted_uses:
  - summary: Export controls
    text: No Software may be downloaded from the Services or otherwise exported or re-exported in violation of U.S. export laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You may be required to register with Hidden Door or provide information about yourself or your parent or guardian
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Hidden Door
provenance_date: '2026-11-09'
provider_name: Hidden Door
provider_slug: hidden-door
slug: hidden-door-eligibility
source_date: '2026-11-09'
source_filename: hidden-door-eligibility.yml
source_heading: Eligibility
source_page: https://www.hiddendoor.co/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Hidden Door\naid: hidden-door\nurl: https://www.hiddendoor.co/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export controls\n  text: No Software may be downloaded from the Services or otherwise exported or re-exported in violation of U.S.\n    export laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You may be required to register with Hidden Door or provide information about yourself or your parent or\n    guardian\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years\
  \ old to use the Services.\n"
source_yaml_url: https://artifacts.apis.io/hidden-door/eligibility/hidden-door-eligibility.yml
stated_fields:
- restricted_uses
- verification
- minimum_age
summary_line: 3 quoted statements, read from Hidden Door's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Storytelling
- Interactive Fiction
- Roleplay
- Gaming
- Entertainment
- User Generated Content
---
