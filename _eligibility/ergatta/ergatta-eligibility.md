---
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served:
    - US
    text: We provide the Services for use only by persons located in the United States.
  entity_types:
  - text: The Services are only for users who are 13 years of age or older.
    type: individual
  minimum_age:
    text: The Services are only for users who are 13 years of age or older.
    value: '13'
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
name: Ergatta
provenance_date: '2026-11-09'
provider_name: Ergatta
provider_slug: ergatta
slug: ergatta-eligibility
source_date: '2026-11-09'
source_filename: ergatta-eligibility.yml
source_heading: Eligibility
source_page: https://ergatta.com/pages/ergatta-terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Ergatta\naid: ergatta\nurl: https://ergatta.com/pages/ergatta-terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served:\n  - US\n  excluded: []\n  text: We provide the Services for use only by persons located in the United States.\nentity_types:\n- type: individual\n  text: The Services are only for users who are 13 years of age or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: The Services are only for users who are 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/ergatta/eligibility/ergatta-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Ergatta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Connected Fitness
- Rowing
- Fitness
- Hardware
- Gaming
- Consumer
- Direct to Consumer
---
