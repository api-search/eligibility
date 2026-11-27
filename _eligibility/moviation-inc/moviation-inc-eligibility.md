---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'You must: be at least 18 years old; provide accurate information; have legal capacity to enter contracts; comply with applicable laws.'
    type: individual
  - text: Corporate memberships may only be created by authorized representatives.
    type: business
  minimum_age:
    text: 'You must: be at least 18 years old;'
    value: '18'
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
name: Moviation
provenance_date: '2026-11-10'
provider_name: Moviation
provider_slug: moviation-inc
slug: moviation-inc-eligibility
source_date: '2026-11-10'
source_filename: moviation-inc-eligibility.yml
source_heading: Eligibility
source_page: https://vonaer.com/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moviation\naid: moviation-inc\nurl: https://vonaer.com/legal/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'You must: be at least 18 years old; provide accurate information; have legal capacity to enter contracts;\n    comply with applicable laws.'\n- type: business\n  text: Corporate memberships may only be created by authorized representatives.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: 'You must: be at least 18 years old;'\n"
source_yaml_url: https://artifacts.apis.io/moviation-inc/eligibility/moviation-inc-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Moviation's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Mobility
- Air Taxi
- Urban Air Mobility
- eVTOL
- Aviation
- Luxury Travel
- Transportation
---
