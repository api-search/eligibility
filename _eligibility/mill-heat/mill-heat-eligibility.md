---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You hereby represent and warrant that you are not located in a country that is subject to a U.S. Government embargo
  entity_types:
  - text: solely for your own personal and non-commercial purposes
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: You may not use the App (a) in a manner that violates any local, national, foreign or international law
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: In order to use the App, you must first create a Mill Account
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Mill (heaters)
provenance_date: '2026-11-10'
provider_name: Mill (heaters)
provider_slug: mill-heat
slug: mill-heat-eligibility
source_date: '2026-11-10'
source_filename: mill-heat-eligibility.yml
source_heading: Eligibility
source_page: https://millnorway.com/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Mill (heaters)\naid: mill-heat\nurl: https://millnorway.com/terms-of-use/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You hereby represent and warrant that you are not located in a country that is subject to a U.S. Government\n    embargo\nentity_types:\n- type: individual\n  text: solely for your own personal and non-commercial purposes\nrestricted_uses:\n- summary: Unlawful use\n  text: You may not use the App (a) in a manner that violates any local, national, foreign or international law\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: In order\
  \ to use the App, you must first create a Mill Account\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mill-heat/eligibility/mill-heat-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from Mill (heaters)'s own page on 2026-11-10.
synthetic: false
tags:
- Company
- Heating
- IoT
- ScandinavianDesign
- Energy Efficiency
---
