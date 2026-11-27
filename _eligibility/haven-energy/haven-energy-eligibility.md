---
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: To access and use the Platform, you must be 18 years of age or older and located in the United States.
  entity_types:
  - text: To access and use the Platform, you must be 18 years of age or older and located in the United States.
    type: individual
  minimum_age:
    text: you must be 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Embargoed or restricted-party users
    text: you are not located in a country that is subject to a United States government embargo
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
name: Haven Energy
provenance_date: '2026-11-09'
provider_name: Haven Energy
provider_slug: haven-energy
slug: haven-energy-eligibility
source_date: '2026-11-09'
source_filename: haven-energy-eligibility.yml
source_heading: Eligibility
source_page: https://havenenergy.com/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Haven Energy\naid: haven-energy\nurl: https://havenenergy.com/terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: To access and use the Platform, you must be 18 years of age or older and located in the United States.\nentity_types:\n- type: individual\n  text: To access and use the Platform, you must be 18 years of age or older and located in the United States.\nrestricted_uses:\n- summary: Embargoed or restricted-party users\n  text: you are not located in a country that is subject to a United States government embargo\nverification:\n  kyc: null\n  kyb: null\n\
  \  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/haven-energy/eligibility/haven-energy-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Haven Energy's own page on 2026-11-09.
synthetic: false
tags:
- Energy
- Energy Storage
- Solar
- Virtual Power Plant
- Distributed Energy Resources
- Home Battery
- Clean Energy
- Utilities
- Climate Tech
- Company
---
