---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Company controls and operates the Services from various locations and makes no representation that the Services are appropriate or available for use in all locations.
  entity_types:
  - text: You must be at least 18 years old to use and access the App.
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use and access the App.
    value: '18'
  restricted_uses:
  - summary: Export and sanctions restrictions
    text: You represent and warrant that you are (1) not located in any country or region that is subject to a U.S. government embargo and (2) are not a denied party as specified in the regulations listed above.
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
name: Pallie
provenance_date: '2026-11-10'
provider_name: Pallie
provider_slug: pallie
slug: pallie-eligibility
source_date: '2026-11-10'
source_filename: pallie-eligibility.yml
source_heading: Eligibility
source_page: https://pallie.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pallie\naid: pallie\nurl: https://pallie.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Company controls and operates the Services from various locations and makes no representation that the\n    Services are appropriate or available for use in all locations.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use and access the App.\nrestricted_uses:\n- summary: Export and sanctions restrictions\n  text: You represent and warrant that you are (1) not located in any country or region that is subject to a U.S.\n    government embargo and\
  \ (2) are not a denied party as specified in the regulations listed above.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use and access the App.\n"
source_yaml_url: https://artifacts.apis.io/pallie/eligibility/pallie-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Pallie's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Personal Companion
- Mental Health
- Productivity
---
