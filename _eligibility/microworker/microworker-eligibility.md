---
api_specs:
- filename: microworker-v1-openapi.json
  format: json
  label: Microworker API V1 API
  slug: microworker-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/microworker/openapi/_original/microworker-v1-openapi.json
claim_count: 5
description: ''
doc:
  countries:
    excluded:
    - CU
    - IR
    - KP
    served: []
    text: Microworker isn't available to people in Cuba, Iran, North Korea, or the Crimea, Donetsk and Luhansk regions of Ukraine.
  entity_types:
  - text: You must be at least 13 years old to use Microworker. If you are under 18, you need your parent's or legal guardian's permission, and they accept these Terms for you.
    type: individual
  minimum_age:
    text: You must be at least 13 years old to use Microworker.
    value: '13'
  restricted_uses:
  - summary: Adult-only (18+) tasks
    text: Some tasks are for adults only (18+) — for example, tasks about gambling or adult content.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: you must confirm that you are 18 or older before you take one.
excluded_countries:
- CU
- IR
- KP
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Microworker
provenance_date: '2026-11-10'
provider_name: Microworker
provider_slug: microworker
slug: microworker-eligibility
source_date: '2026-11-10'
source_filename: microworker-eligibility.yml
source_heading: Eligibility
source_page: https://microworker.app/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Microworker\naid: microworker\nurl: https://microworker.app/terms/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded:\n  - CU\n  - IR\n  - KP\n  text: Microworker isn't available to people in Cuba, Iran, North Korea, or the Crimea, Donetsk and Luhansk regions\n    of Ukraine.\nentity_types:\n- type: individual\n  text: You must be at least 13 years old to use Microworker. If you are under 18, you need your parent's or legal\n    guardian's permission, and they accept these Terms for you.\nrestricted_uses:\n- summary: Adult-only (18+) tasks\n  text: Some tasks are for adults only (18+) — for example,\
  \ tasks about gambling or adult content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: you must confirm that you are 18 or older before you take one.\nminimum_age:\n  value: '13'\n  text: You must be at least 13 years old to use Microworker.\n"
source_yaml_url: https://artifacts.apis.io/microworker/eligibility/microworker-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Microworker's own page on 2026-11-10.
synthetic: false
tags:
- Marketplace
- Data Entry
- Testing
- Surveys
- Social Media Engagement
---
