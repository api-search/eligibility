---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a “Consumer” is any individual entering into the contract for a purpose not related to the individual’s business, trade or self-employed professional activity
    type: individual
  - text: a Business Customer is a user (whether an individual, company or partnership vested with legal capacity) who enters into the relevant contract in the conduct of its business or self-employed professional activity
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful content
    text: Unlawful or promoting unlawful activity.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: The usage of the Service requires the registration as well as the set-up of a user account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Superlist
provenance_date: '2026-11-10'
provider_name: Superlist
provider_slug: superlist
slug: superlist-eligibility
source_date: '2026-11-10'
source_filename: superlist-eligibility.yml
source_heading: Eligibility
source_page: https://www.superlist.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Superlist\naid: superlist\nurl: https://www.superlist.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a “Consumer” is any individual entering into the contract for a purpose not related to the individual’s\n    business, trade or self-employed professional activity\n- type: business\n  text: a Business Customer is a user (whether an individual, company or partnership vested with legal capacity)\n    who enters into the relevant contract in the conduct of its business or self-employed professional activity\nrestricted_uses:\n\
  - summary: Unlawful content\n  text: Unlawful or promoting unlawful activity.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: The usage of the Service requires the registration as well as the set-up of a user account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/superlist/eligibility/superlist-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Superlist's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Project Management Sector
- Task Management
- Productivity
- To-Do Lists
- Collaboration
- MCP
- Agents
- AI Assistant
---
