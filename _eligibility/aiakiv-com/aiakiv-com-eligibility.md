---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be old enough to form a binding contract in your jurisdiction.
    type: individual
  minimum_age:
    text: You must be old enough to form a binding contract in your jurisdiction.
    value: null
  restricted_uses:
  - summary: Unlawful, infringing, abusive or harmful uses
    text: 'Do not use the Service, and do not let other people or AI agents use it through your account, for any of the following:'
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
name: AiAkiv
provenance_date: '2026-11-09'
provider_name: AiAkiv
provider_slug: aiakiv-com
slug: aiakiv-com-eligibility
source_date: '2026-11-09'
source_filename: aiakiv-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.aiakiv.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AiAkiv\naid: aiakiv-com\nurl: https://www.aiakiv.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be old enough to form a binding contract in your jurisdiction.\nrestricted_uses:\n- summary: Unlawful, infringing, abusive or harmful uses\n  text: 'Do not use the Service, and do not let other people or AI agents use it through your account, for any of\n    the following:'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be old enough to\
  \ form a binding contract in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/aiakiv-com/eligibility/aiakiv-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from AiAkiv's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Knowledge Management
- Team Collaboration
- Memory
- RAG
---
