---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Site is controlled and operated from facilities in the United States. You may not use the Site if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United States government.
  entity_types:
  - text: You must be at least 18 years old to use the Site and Services.
    type: individual
  - text: 'If you open a Clutter Account on behalf of a company, organization, or other entity, then: (a) “you” includes you and that entity'
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Site and Services.
    value: '18'
  restricted_uses:
  - summary: Commercial solicitation prohibited
    text: using the Site for any commercial solicitation purposes
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
name: Clutter
provenance_date: '2026-11-09'
provider_name: Clutter
provider_slug: clutter
slug: clutter-eligibility
source_date: '2026-11-09'
source_filename: clutter-eligibility.yml
source_heading: Eligibility
source_page: https://www.clutter.com/legal/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Clutter\naid: clutter\nurl: https://www.clutter.com/legal/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: The Site is controlled and operated from facilities in the United States. You may not use the Site if you\n    are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied\n    by the United States government.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Site and Services.\n- type: business\n  text: 'If you open a Clutter Account on behalf of a company, organization,\
  \ or other entity, then: (a) “you” includes\n    you and that entity'\nrestricted_uses:\n- summary: Commercial solicitation prohibited\n  text: using the Site for any commercial solicitation purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Site and Services.\n"
source_yaml_url: https://artifacts.apis.io/clutter/eligibility/clutter-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Clutter's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Consumer
- Storage
- Moving
- Logistics
- On-Demand
- Warehousing
- Iron Mountain
---
