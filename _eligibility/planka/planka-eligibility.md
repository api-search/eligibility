---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Provider's offerings are directed exclusively at businesses and professionals
    type: business
  - text: at legal persons under public law and at special funds under public law
    type: government
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful or sanctioned use
    text: Use in sanctioned countries or by sanctioned persons is prohibited.
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
name: PLANKA
provenance_date: '2026-11-10'
provider_name: PLANKA
provider_slug: planka
slug: planka-eligibility
source_date: '2026-11-10'
source_filename: planka-eligibility.yml
source_heading: Eligibility
source_page: https://planka.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: PLANKA\naid: planka\nurl: https://planka.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: The Provider's offerings are directed exclusively at businesses and professionals\n- type: government\n  text: at legal persons under public law and at special funds under public law\nrestricted_uses:\n- summary: Unlawful or sanctioned use\n  text: Use in sanctioned countries or by sanctioned persons is prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/planka/eligibility/planka-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from PLANKA's own page on 2026-11-10.
synthetic: false
tags:
- Kanban
- Project Management
- Self-Hosted
- Agile
- Open Source
---
