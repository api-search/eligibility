---
api_specs:
- filename: engine-yard-openapi-generated.yml
  format: yaml
  label: Engine Yard API
  slug: engine-yard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/engine-yard/openapi/_ae-authored/engine-yard-openapi-generated.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - RU
    - BY
    - SY
    served: []
    text: Currently such jurisdictions are Cuba, Iran, North Korea, , the territory of Crimea the Donetsk and Luhansk oblasts of Ukraine, Russia, Belarus and Syria
  entity_types:
  - text: IF YOU ARE ACCEPTING THESE TERMS OF SERVICE IN YOUR INDIVIDUAL CAPACITY
    type: individual
  - text: THE COMPANY OF WHICH YOU ARE A DULY AUTHORIZED EMPLOYEE OR AGENT
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control compliance
    text: Customer agrees to comply with all applicable Export Laws in connection with Customer’s use of the Company Offerings.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- RU
- BY
- SY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Engine Yard
provenance_date: '2026-11-09'
provider_name: Engine Yard
provider_slug: engine-yard
slug: engine-yard-eligibility
source_date: '2026-11-09'
source_filename: engine-yard-eligibility.yml
source_heading: Eligibility
source_page: https://www.engineyard.com/policies/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Engine Yard\naid: engine-yard\nurl: https://www.engineyard.com/policies/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - RU\n  - BY\n  - SY\n  text: Currently such jurisdictions are Cuba, Iran, North Korea, , the territory of Crimea the Donetsk and Luhansk\n    oblasts of Ukraine, Russia, Belarus and Syria\nentity_types:\n- type: individual\n  text: IF YOU ARE ACCEPTING THESE TERMS OF SERVICE IN YOUR INDIVIDUAL CAPACITY\n- type: business\n  text: THE COMPANY OF WHICH YOU ARE A DULY AUTHORIZED EMPLOYEE OR AGENT\nrestricted_uses:\n- summary: Export\
  \ control compliance\n  text: Customer agrees to comply with all applicable Export Laws in connection with Customer’s use of the Company\n    Offerings.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/engine-yard/eligibility/engine-yard-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Engine Yard's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Platform-as-a-Service
- Ruby
- Ruby on Rails
- Cloud Hosting
---
