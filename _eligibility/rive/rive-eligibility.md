---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you, in your individual capacity, or on behalf of the entity you represent
    type: individual
  - text: If you (or your organization, including any parent or affiliate entities) have annual gross revenues exceeding USD $10 million, you may only use the Services under our Enterprise plan.
    type: business
  minimum_age:
    text: You may use the Services only if you are 13 years or older and are not barred from using the Services under applicable law.
    value: '13'
  restricted_uses:
  - summary: Automated decision-making without human review
    text: use the AI Features for automated decision-making that has legal or similarly significant effects on individuals without appropriate human review and compliance with applicable law
  - summary: Sanctioned persons
    text: You may not use Rive if you are or are working on behalf of a Specially Designated National (SDN)
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
name: Rive
provenance_date: '2026-11-10'
provider_name: Rive
provider_slug: rive
slug: rive-eligibility
source_date: '2026-11-10'
source_filename: rive-eligibility.yml
source_heading: Eligibility
source_page: https://rive.app/docs/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rive\naid: rive\nurl: https://rive.app/docs/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: you, in your individual capacity, or on behalf of the entity you represent\n- type: business\n  text: If you (or your organization, including any parent or affiliate entities) have annual gross revenues exceeding\n    USD $10 million, you may only use the Services under our Enterprise plan.\nrestricted_uses:\n- summary: Automated decision-making without human review\n  text: use the AI Features for automated decision-making\
  \ that has legal or similarly significant effects on individuals\n    without appropriate human review and compliance with applicable law\n- summary: Sanctioned persons\n  text: You may not use Rive if you are or are working on behalf of a Specially Designated National (SDN)\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You may use the Services only if you are 13 years or older and are not barred from using the Services under\n    applicable law.\n"
source_yaml_url: https://artifacts.apis.io/rive/eligibility/rive-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Rive's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Graphics
- Animation
- Design
- Interactive
- Runtime
- Vector Graphics
- Game Development
- Rendering
- SDK
- WebAssembly
- State Machine
---
