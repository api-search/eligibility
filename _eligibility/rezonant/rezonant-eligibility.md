---
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Supplier may offer a free tier of the Services to individual users and businesses
    type: individual
  - text: The Customer may use the Platform only as needed to access the Services for its internal business purposes or personal use
    type: business
  minimum_age:
    text: null
    value: null
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
name: Rezonant
provenance_date: '2026-11-10'
provider_name: Rezonant
provider_slug: rezonant
slug: rezonant-eligibility
source_date: '2026-11-10'
source_filename: rezonant-eligibility.yml
source_heading: Eligibility
source_page: https://rezonant.app/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rezonant\naid: rezonant\nurl: https://rezonant.app/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Supplier may offer a free tier of the Services to individual users and businesses\n- type: business\n  text: The Customer may use the Platform only as needed to access the Services for its internal business purposes\n    or personal use\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/rezonant/eligibility/rezonant-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Rezonant's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Product Management
- Software Development
- AI Agents
- Developer Tools
- Engineering
- Project Management
---
