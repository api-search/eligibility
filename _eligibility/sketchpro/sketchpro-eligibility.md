---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"Customer" means any organization or individual that has entered into a subscription or services agreement with Company.'
    type: individual
  - text: '"Customer" means any organization or individual that has entered into a subscription or services agreement with Company.'
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or regulations
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
name: Sketchpro
provenance_date: '2026-11-10'
provider_name: Sketchpro
provider_slug: sketchpro
slug: sketchpro-eligibility
source_date: '2026-11-10'
source_filename: sketchpro-eligibility.yml
source_heading: Eligibility
source_page: https://sketchpro.ai/copilot/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sketchpro\naid: sketchpro\nurl: https://sketchpro.ai/copilot/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"Customer\" means any organization or individual that has entered into a subscription or services agreement\n    with Company.'\n- type: business\n  text: '\"Customer\" means any organization or individual that has entered into a subscription or services agreement\n    with Company.'\nrestricted_uses:\n- summary: Export restrictions\n  text: Customer may not remove or export from the United States or allow the\
  \ export or re-export of the Services,\n    Software or anything related thereto, or any direct product thereof in violation of any restrictions, laws or\n    regulations\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sketchpro/eligibility/sketchpro-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Sketchpro's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Architecture
- Construction
- AEC
- Revit
- BIM
- Documentation
- Copilot
- Productivity
---
