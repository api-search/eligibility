---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: THE INDIVIDUAL ACCEPTING THIS AGREEMENT DOES SO ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY (“Customer”)
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No sanctions violations
    text: use or access the Service in violation of U.S. or applicable non-U.S. laws relating to economic or trade sanctions
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
name: Linear
provenance_date: '2026-11-09'
provider_name: Linear
provider_slug: linear-app
slug: linear-app-eligibility
source_date: '2026-11-09'
source_filename: linear-app-eligibility.yml
source_heading: Eligibility
source_page: https://linear.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Linear\naid: linear-app\nurl: https://linear.app/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: THE INDIVIDUAL ACCEPTING THIS AGREEMENT DOES SO ON BEHALF OF A COMPANY OR OTHER LEGAL ENTITY (“Customer”)\nrestricted_uses:\n- summary: No sanctions violations\n  text: use or access the Service in violation of U.S. or applicable non-U.S. laws relating to economic or trade\n    sanctions\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/linear-app/eligibility/linear-app-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Linear's own page on 2026-11-09.
synthetic: false
tags:
- Project Management
- Issue Tracking
- Productivity
- Software-as-a-Service
- GraphQL
- Developer Tools
- Agents
---
