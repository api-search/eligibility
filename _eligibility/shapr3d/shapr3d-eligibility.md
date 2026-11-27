---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: for its own lawful personal use (for consumer Customers)
    type: individual
  - text: lawful internal business purposes (for business Customers)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Free version non-commercial only
    text: use it solely for non-commercial, personal purposes and not for any business, commercial, or revenue-generating activities
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
name: Shapr3D
provenance_date: '2026-11-10'
provider_name: Shapr3D
provider_slug: shapr3d
slug: shapr3d-eligibility
source_date: '2026-11-10'
source_filename: shapr3d-eligibility.yml
source_heading: Eligibility
source_page: https://www.shapr3d.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Shapr3D\naid: shapr3d\nurl: https://www.shapr3d.com/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: for its own lawful personal use (for consumer Customers)\n- type: business\n  text: lawful internal business purposes (for business Customers)\nrestricted_uses:\n- summary: Free version non-commercial only\n  text: use it solely for non-commercial, personal purposes and not for any business, commercial, or revenue-generating\n    activities\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/shapr3d/eligibility/shapr3d-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Shapr3D's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Software-as-a-Service
- CAD
- 3D Modeling
- Design
- Engineering
- Product Design
- Parametric Modeling
---
