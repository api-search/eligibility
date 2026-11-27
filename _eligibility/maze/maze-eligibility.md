---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: Services are accessible only where the user is resident in a country from which the Services are accessible.
  entity_types:
  - text: The Services are intended for use by Customer in a commercial or professional capacity and are not intended for consumers or in a personal capacity.
    type: business
  minimum_age:
    text: you must be 18 years of age and be resident in a country from which the Services are accessible.
    value: '18'
  restricted_uses:
  - summary: Sanctioned jurisdictions and parties
    text: Customer is not located in a country that is subject to financial, economic or trade sanctions or embargoes
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
name: Maze
provenance_date: '2026-11-10'
provider_name: Maze
provider_slug: maze
slug: maze-eligibility
source_date: '2026-11-10'
source_filename: maze-eligibility.yml
source_heading: Eligibility
source_page: https://maze.co/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Maze\naid: maze\nurl: https://maze.co/tos/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: Services are accessible only where the user is resident in a country from which the Services are accessible.\nentity_types:\n- type: business\n  text: The Services are intended for use by Customer in a commercial or professional capacity and are not intended\n    for consumers or in a personal capacity.\nrestricted_uses:\n- summary: Sanctioned jurisdictions and parties\n  text: Customer is not located in a country that is subject to financial, economic or trade sanctions or embargoes\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be 18 years of age and be resident in a country from which the Services are accessible.\n"
source_yaml_url: https://artifacts.apis.io/maze/eligibility/maze-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Maze's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- User Research
- Product Research
- Usability Testing
- Surveys
- Prototype Testing
- Product Discovery
- Software-as-a-Service
---
