---
api_specs:
- filename: runcrate-api-openapi.json
  format: json
  label: Runcrate API API
  slug: runcrate-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/runcrate/openapi/_original/runcrate-api-openapi.json
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    - SY
    - RU
    - BY
    served: []
    text: 'You may not use Runcrate: From, or for the benefit of anyone in, a country or region under comprehensive US sanctions, currently Cuba, Iran, North Korea, Syria, Russia, Belarus, and the Crimea, Donetsk and Luhansk regions of Ukraine'
  entity_types:
  - text: You must be at least 18 years old to use Runcrate. If you are 13 to 17, you may use Runcrate only with the permission of a parent or legal guardian
    type: individual
  minimum_age:
    text: You must be at least 18 years old to use Runcrate.
    value: '18'
  restricted_uses:
  - summary: Weapons of mass destruction
    text: For weapons of mass destruction, including nuclear, chemical or biological weapons and the missiles that deliver them
  - summary: Military end uses
    text: For military end uses or by military end users where US or other applicable law restricts them
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: null
excluded_countries:
- CU
- IR
- KP
- SY
- RU
- BY
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Runcrate
provenance_date: '2026-11-10'
provider_name: Runcrate
provider_slug: runcrate
slug: runcrate-eligibility
source_date: '2026-11-10'
source_filename: runcrate-eligibility.yml
source_heading: Eligibility
source_page: https://www.runcrate.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Runcrate\naid: runcrate\nurl: https://www.runcrate.ai/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  - SY\n  - RU\n  - BY\n  text: 'You may not use Runcrate: From, or for the benefit of anyone in, a country or region under comprehensive\n    US sanctions, currently Cuba, Iran, North Korea, Syria, Russia, Belarus, and the Crimea, Donetsk and Luhansk\n    regions of Ukraine'\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use Runcrate. If you are 13 to 17, you may use Runcrate only with the\n    permission of a parent or legal\
  \ guardian\nrestricted_uses:\n- summary: Weapons of mass destruction\n  text: For weapons of mass destruction, including nuclear, chemical or biological weapons and the missiles that\n    deliver them\n- summary: Military end uses\n  text: For military end uses or by military end users where US or other applicable law restricts them\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use Runcrate.\n"
source_yaml_url: https://artifacts.apis.io/runcrate/eligibility/runcrate-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Runcrate's own page on 2026-11-10.
synthetic: false
tags:
- Artificial Intelligence
- GPU
- Inference
- Compute
- Platform
---
