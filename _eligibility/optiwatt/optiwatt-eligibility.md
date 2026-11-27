---
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Company Services if you are barred from doing so under the laws of the United States or other countries including the country in which you are resident or from which you use or access the Company Services.
  entity_types:
  - text: You must be at least 16 years old to use the Company Services.
    type: individual
  - text: '"You" or "your" refers to you as the individual using the Company Services, the company or other legal entity represented by such individual, and all affiliates thereto.'
    type: business
  minimum_age:
    text: You must be at least 16 years old to use the Company Services.
    value: '16'
  restricted_uses:
  - summary: Competitors and benchmarking
    text: 'You will not use or access the Company Services: (a) if you are a competitor of us or operating on behalf of such a competitor'
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
name: Optiwatt
provenance_date: '2026-11-10'
provider_name: Optiwatt
provider_slug: optiwatt
slug: optiwatt-eligibility
source_date: '2026-11-10'
source_filename: optiwatt-eligibility.yml
source_heading: Eligibility
source_page: https://optiwatt.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Optiwatt\naid: optiwatt\nurl: https://optiwatt.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Company Services if you are barred from doing so under the laws of the United States\n    or other countries including the country in which you are resident or from which you use or access the Company\n    Services.\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use the Company Services.\n- type: business\n  text: '\"You\" or \"your\" refers to you as the individual using the Company Services, the company or other legal\n   \
  \ entity represented by such individual, and all affiliates thereto.'\nrestricted_uses:\n- summary: Competitors and benchmarking\n  text: 'You will not use or access the Company Services: (a) if you are a competitor of us or operating on behalf\n    of such a competitor'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use the Company Services.\n"
source_yaml_url: https://artifacts.apis.io/optiwatt/eligibility/optiwatt-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Optiwatt's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Frontier Tech
- Energy
- Energy Management
- Electric Vehicles
- EV Charging
- Smart Home
- DERMS
- Demand Response
- Utilities
- Virtual Power Plant
---
