---
api_specs:
- filename: dexterity-games-api-openapi.yml
  format: yaml
  label: Dexterity Games API
  slug: dexterity-games-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexterity/openapi/dexterity-games-api-openapi.yml
- filename: dexterity-leaderboard-api-openapi.yml
  format: yaml
  label: Dexterity Leaderboard API
  slug: dexterity-leaderboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexterity/openapi/dexterity-leaderboard-api-openapi.yml
- filename: dexterity-players-api-openapi.yml
  format: yaml
  label: Dexterity Players API
  slug: dexterity-players-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexterity/openapi/dexterity-players-api-openapi.yml
- filename: dexterity-system-api-openapi.yml
  format: yaml
  label: Dexterity System API
  slug: dexterity-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dexterity/openapi/dexterity-system-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 16 years old to use our Site.
    type: individual
  minimum_age:
    text: You must be at least 16 years old to use our Site.
    value: '16'
  restricted_uses:
  - summary: Under-16 users
    text: You must be at least 16 years old to use our Site.
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
name: Dexterity
provenance_date: '2026-11-09'
provider_name: Dexterity
provider_slug: dexterity
slug: dexterity-eligibility
source_date: '2026-11-09'
source_filename: dexterity-eligibility.yml
source_heading: Eligibility
source_page: https://dexterity.ai/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dexterity\naid: dexterity\nurl: https://dexterity.ai/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 16 years old to use our Site.\nrestricted_uses:\n- summary: Under-16 users\n  text: You must be at least 16 years old to use our Site.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You must be at least 16 years old to use our Site.\n"
source_yaml_url: https://artifacts.apis.io/dexterity/eligibility/dexterity-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Dexterity's own page on 2026-11-09.
synthetic: false
tags:
- Physical AI
- Industrial Robotics
- Robotics
- Warehouse Automation
- Logistics
- Manufacturing
- World Model
- Foresight
- Mech
- Dual-Arm
- Truck Loading
- Palletizing
- Depalletizing
- Singulation
- Research API
- Packing Challenge
---
