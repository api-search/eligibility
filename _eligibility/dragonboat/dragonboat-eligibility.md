---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If You are entering into this Agreement on behalf of a company, organization or another legal entity (an “Entity”), You are agreeing to this Agreement for that Entity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: US export restrictions
    text: Customer may not remove or export from the United States or allow the export or re-export of the Services, Software or anything related thereto
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
name: Dragonboat
provenance_date: '2026-11-09'
provider_name: Dragonboat
provider_slug: dragonboat
slug: dragonboat-eligibility
source_date: '2026-11-09'
source_filename: dragonboat-eligibility.yml
source_heading: Eligibility
source_page: https://dragonboat.io/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dragonboat\naid: dragonboat\nurl: https://dragonboat.io/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If You are entering into this Agreement on behalf of a company, organization or another legal entity (an\n    “Entity”), You are agreeing to this Agreement for that Entity\nrestricted_uses:\n- summary: US export restrictions\n  text: Customer may not remove or export from the United States or allow the export or re-export of the Services,\n    Software or anything related thereto\nverification:\n  kyc: null\n  kyb:\
  \ null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/dragonboat/eligibility/dragonboat-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Dragonboat's own page on 2026-11-09.
synthetic: false
tags:
- Product Management
- Portfolio Management
- AI Integration
- Enterprise Software
- Agile
---
