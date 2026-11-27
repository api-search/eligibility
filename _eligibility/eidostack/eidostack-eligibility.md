---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be legally able to enter a binding agreement where you live.
    type: individual
  - text: “User,” “you,” and “your” mean the person or organization using the Service.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Lawful use only
    text: You may not use the Service if your use would violate applicable law or a third-party agreement.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: We may require reasonable information to verify an account or investigate abuse.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: EidoStack
provenance_date: '2026-11-09'
provider_name: EidoStack
provider_slug: eidostack
slug: eidostack-eligibility
source_date: '2026-11-09'
source_filename: eidostack-eligibility.yml
source_heading: Eligibility
source_page: https://eidostack.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: EidoStack\naid: eidostack\nurl: https://eidostack.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be legally able to enter a binding agreement where you live.\n- type: business\n  text: “User,” “you,” and “your” mean the person or organization using the Service.\nrestricted_uses:\n- summary: Lawful use only\n  text: You may not use the Service if your use would violate applicable law or a third-party agreement.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: We may require reasonable\
  \ information to verify an account or investigate abuse.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eidostack/eligibility/eidostack-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from EidoStack's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Model Evaluation
- Platform
- Software-as-a-Service
---
