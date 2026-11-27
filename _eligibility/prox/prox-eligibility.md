---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: use the Services only for Customer's internal business purposes unless an order form permits external use
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Human review of AI outputs
    text: Customer is responsible for reviewing outputs before relying on them for customer-facing, safety-critical, regulated, financial, legal, engineering, procurement, or operational decisions.
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
name: Prox
provenance_date: '2026-11-10'
provider_name: Prox
provider_slug: prox
slug: prox-eligibility
source_date: '2026-11-10'
source_filename: prox-eligibility.yml
source_heading: Eligibility
source_page: https://useprox.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Prox\naid: prox\nurl: https://useprox.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: use the Services only for Customer's internal business purposes unless an order form permits external use\nrestricted_uses:\n- summary: Human review of AI outputs\n  text: Customer is responsible for reviewing outputs before relying on them for customer-facing, safety-critical,\n    regulated, financial, legal, engineering, procurement, or operational decisions.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/prox/eligibility/prox-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Prox's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- MCP
- Manufacturing
- Product Support
- Knowledge Base
- Documentation
- Agents
---
