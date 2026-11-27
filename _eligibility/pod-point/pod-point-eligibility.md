---
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served:
    - GB
    - IE
    - 'NO'
    - ES
    - FR
    text: The terms which apply to you will depend on the country in which you are currently active.
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
name: Pod Point
provenance_date: '2026-11-10'
provider_name: Pod Point
provider_slug: pod-point
slug: pod-point-eligibility
source_date: '2026-11-10'
source_filename: pod-point-eligibility.yml
source_heading: Eligibility
source_page: https://podenergy.com/general-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Pod Point\naid: pod-point\nurl: https://podenergy.com/general-terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - GB\n  - IE\n  - 'NO'\n  - ES\n  - FR\n  excluded: []\n  text: The terms which apply to you will depend on the country in which you are currently active.\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/pod-point/eligibility/pod-point-eligibility.yml
stated_fields:
- countries
summary_line: 1 quoted statement, read from Pod Point's own page on 2026-11-10.
synthetic: false
tags:
- Energy
- United Kingdom
- EV Charging
- Electric Vehicles
- Utilities
- Electricity
- OCPI
- Charge Point Operator
- Smart Charging
- Grid
---
