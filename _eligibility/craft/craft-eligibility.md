---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Family Plan is intended solely for personal, non-commercial use by individuals who are part of the same household, family, or close personal circle
    type: individual
  minimum_age:
    text: You may not use the Service if you are under 16 years of age (or other age as required by local law).
    value: '16'
  restricted_uses:
  - summary: Family Plan commercial use
    text: The Family Plan may not be used for any commercial, professional, or business-related purposes.
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
name: craft
provenance_date: '2026-11-09'
provider_name: craft
provider_slug: craft
slug: craft-eligibility
source_date: '2026-11-09'
source_filename: craft-eligibility.yml
source_heading: Eligibility
source_page: https://www.craft.do/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: craft\naid: craft\nurl: https://www.craft.do/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Family Plan is intended solely for personal, non-commercial use by individuals who are part of the same\n    household, family, or close personal circle\nrestricted_uses:\n- summary: Family Plan commercial use\n  text: The Family Plan may not be used for any commercial, professional, or business-related purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text:\
  \ You may not use the Service if you are under 16 years of age (or other age as required by local law).\n"
source_yaml_url: https://artifacts.apis.io/craft/eligibility/craft-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from craft's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Productivity
- Notes
- Documents
- Note Taking
- Task
- Collaboration
- Writing
- Artificial Intelligence
- MCP
- Extensions
---
