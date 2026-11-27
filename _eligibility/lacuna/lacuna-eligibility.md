---
api_specs:
- filename: lacuna-lacuna-music-api-api-openapi.yml
  format: yaml
  label: Lacuna Music API Events
  slug: lacuna-lacuna-music-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lacuna/openapi/lacuna-lacuna-music-api-api-openapi.yml
- filename: lacuna-music-api-openapi.yml
  format: yaml
  label: Lacuna Music API
  slug: lacuna-music-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lacuna/openapi/lacuna-music-api-openapi.yml
- filename: lacuna-account-api-openapi.yml
  format: yaml
  label: Lacuna Account API
  slug: lacuna-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lacuna/openapi/lacuna-account-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided is not intended for use where contrary to law or regulation. Accessing from other locations is your responsibility, and you must comply with local laws.
  entity_types:
  - text: These Legal Terms are a binding agreement between you (personally or on behalf of an entity)
    type: individual
  minimum_age:
    text: The Services are for users 18 and older.
    value: '18'
  restricted_uses:
  - summary: Prohibited AI uses
    text: 'Voice Cloning Without Consent: Creating, attempting to create, or distributing AI-generated audio that replicates or imitates a real person''s voice without their explicit consent.'
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
name: Lacuna
provenance_date: '2026-11-09'
provider_name: Lacuna
provider_slug: lacuna
slug: lacuna-eligibility
source_date: '2026-11-09'
source_filename: lacuna-eligibility.yml
source_heading: Eligibility
source_page: https://www.lacuna.fm/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lacuna\naid: lacuna\nurl: https://www.lacuna.fm/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided is not intended for use where contrary to law or regulation. Accessing from other\n    locations is your responsibility, and you must comply with local laws.\nentity_types:\n- type: individual\n  text: These Legal Terms are a binding agreement between you (personally or on behalf of an entity)\nrestricted_uses:\n- summary: Prohibited AI uses\n  text: 'Voice Cloning Without Consent: Creating, attempting to create, or distributing AI-generated audio that\n\
  \    replicates or imitates a real person''s voice without their explicit consent.'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Services are for users 18 and older.\n"
source_yaml_url: https://artifacts.apis.io/lacuna/eligibility/lacuna-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Lacuna's own page on 2026-11-09.
synthetic: false
tags:
- AI Music
- Music Generation
- AI Song Generator
- AI Lyrics Generator
- Audio
- MIDI
- Songwriting
- Generative AI
- MCP Server
- Agent Skills
- A2A
- Developer Tools
- Account
- OAuth
- Authentication
---
