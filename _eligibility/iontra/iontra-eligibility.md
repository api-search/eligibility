---
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - RU
    - BY
    served: []
    text: Buyer shall not sell, export, re-export or transfer, directly or indirectly, any Products to (or for use in) Russia, Belarus, or the Crimea region of Ukraine.
  entity_types:
  - text: Evaluation Products are intended solely for product and/or software developers for use in a research and development setting
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Evaluation products not for production
    text: Evaluation Products have no direct function and shall not be used in production applications, or production test platforms, or as test equipment.
  - summary: Military and weapons end uses
    text: 'Buyer may not export, re-export, transfer, purchase, or sell any Product: (i) for a military end use; (ii) to a military end user; or (iii) for the design, development, fabrication, or use of nuclear, chemical, or biological weapons or missile technology.'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Iontra
provenance_date: '2026-11-09'
provider_name: Iontra
provider_slug: iontra
slug: iontra-eligibility
source_date: '2026-11-09'
source_filename: iontra-eligibility.yml
source_heading: Eligibility
source_page: https://iontra.com/terms-conditions/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Iontra\naid: iontra\nurl: https://iontra.com/terms-conditions/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - RU\n  - BY\n  text: Buyer shall not sell, export, re-export or transfer, directly or indirectly, any Products to (or for use\n    in) Russia, Belarus, or the Crimea region of Ukraine.\nentity_types:\n- type: developer\n  text: Evaluation Products are intended solely for product and/or software developers for use in a research and\n    development setting\nrestricted_uses:\n- summary: Evaluation products not for production\n  text: Evaluation Products have no direct function and\
  \ shall not be used in production applications, or production\n    test platforms, or as test equipment.\n- summary: Military and weapons end uses\n  text: 'Buyer may not export, re-export, transfer, purchase, or sell any Product: (i) for a military end use; (ii)\n    to a military end user; or (iii) for the design, development, fabrication, or use of nuclear, chemical, or biological\n    weapons or missile technology.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/iontra/eligibility/iontra-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Iontra's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Batteries
- Battery Charging
- Energy Storage
- Semiconductors
- Microcontrollers
- Embedded Systems
- Electric Vehicles
- Consumer Electronics
- Clean Energy
- Hardware
---
