---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: the entity that has submitted an Order Form (defined below) for the license and use of Numeric's products and services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export compliance
    text: Licensee will comply with all applicable export and import control laws and regulations in its use of the Platform
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
name: Numeric
provenance_date: '2026-11-10'
provider_name: Numeric
provider_slug: numeric
slug: numeric-eligibility
source_date: '2026-11-10'
source_filename: numeric-eligibility.yml
source_heading: Eligibility
source_page: https://www.numeric.io/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Numeric\naid: numeric\nurl: https://www.numeric.io/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: the entity that has submitted an Order Form (defined below) for the license and use of Numeric's products\n    and services\nrestricted_uses:\n- summary: Export compliance\n  text: Licensee will comply with all applicable export and import control laws and regulations in its use of the\n    Platform\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/numeric/eligibility/numeric-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Numeric's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Fintech
- Accounting
- Financial Close
- Reconciliation
- MCP
- Agent Skills
- OAuth
- Authentication
---
