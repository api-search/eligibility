---
api_specs:
- filename: blockade-games-skybox-exports-api-openapi.yml
  format: yaml
  label: Blockade Games Skybox Exports API
  slug: blockade-games-skybox-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockade-games/openapi/blockade-games-skybox-exports-api-openapi.yml
- filename: blockade-games-skyboxes-api-openapi.yml
  format: yaml
  label: Blockade Games Skyboxes API
  slug: blockade-games-skyboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blockade-games/openapi/blockade-games-skyboxes-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Each Individual, Free, or Academic Subscription is licensed to a single named individual accountholder for that individual’s own use
    type: individual
  - text: Customer may not purchase, maintain, or cause to be purchased multiple Individual, Free, or Academic Subscriptions in place of a Business or Enterprise Subscription
    type: business
  minimum_age:
    text: By accessing the Services, You confirm that You are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: 'Free Plan: personal non-commercial use only'
    text: Assets generated under the Free Plan are licensed for personal, non-commercial use only
  - summary: No account sharing or seat farming
    text: Each Individual, Free, or Academic Subscription is licensed to a single named individual accountholder for that individual’s own use, and may not be shared, pooled, or centrally administered on behalf of multiple users.
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
name: Blockade Games
provenance_date: '2026-11-09'
provider_name: Blockade Games
provider_slug: blockade-games
slug: blockade-games-eligibility
source_date: '2026-11-09'
source_filename: blockade-games-eligibility.yml
source_heading: Eligibility
source_page: https://www.blockadelabs.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blockade Games\naid: blockade-games\nurl: https://www.blockadelabs.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Each Individual, Free, or Academic Subscription is licensed to a single named individual accountholder for\n    that individual’s own use\n- type: business\n  text: Customer may not purchase, maintain, or cause to be purchased multiple Individual, Free, or Academic Subscriptions\n    in place of a Business or Enterprise Subscription\nrestricted_uses:\n- summary: 'Free Plan: personal non-commercial\
  \ use only'\n  text: Assets generated under the Free Plan are licensed for personal, non-commercial use only\n- summary: No account sharing or seat farming\n  text: Each Individual, Free, or Academic Subscription is licensed to a single named individual accountholder for\n    that individual’s own use, and may not be shared, pooled, or centrally administered on behalf of multiple users.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: By accessing the Services, You confirm that You are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/blockade-games/eligibility/blockade-games-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Blockade Games's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Artificial Intelligence
- Image Generation
- 3D
- Gaming
- Virtual Reality
- Content Generation
- Skybox
---
