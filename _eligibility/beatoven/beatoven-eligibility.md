---
api_specs:
- filename: beatoven-tasks-api-openapi.yml
  format: yaml
  label: Beatoven.ai Tasks API
  slug: beatoven-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatoven/openapi/beatoven-tasks-api-openapi.yml
- filename: beatoven-tracks-api-openapi.yml
  format: yaml
  label: Beatoven.ai Tracks API
  slug: beatoven-tracks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/beatoven/openapi/beatoven-tracks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old to use the Service.
    type: individual
  - text: If you are an entity, the individual accepting this Agreement on your behalf represents and warrants that he or she has authority to bind you to this Agreement
    type: business
  minimum_age:
    text: You must be at least 18 years old to use the Service.
    value: '18'
  restricted_uses:
  - summary: Prohibited content
    text: Is associated with any form of gambling, betting, lottery & bingo type services
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
name: Beatoven.ai
provenance_date: '2026-11-09'
provider_name: Beatoven.ai
provider_slug: beatoven
slug: beatoven-eligibility
source_date: '2026-11-09'
source_filename: beatoven-eligibility.yml
source_heading: Eligibility
source_page: https://www.beatoven.ai/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Beatoven.ai\naid: beatoven\nurl: https://www.beatoven.ai/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old to use the Service.\n- type: business\n  text: If you are an entity, the individual accepting this Agreement on your behalf represents and warrants that\n    he or she has authority to bind you to this Agreement\nrestricted_uses:\n- summary: Prohibited content\n  text: Is associated with any form of gambling, betting, lottery & bingo type services\nverification:\n  kyc: null\n  kyb: null\n \
  \ approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old to use the Service.\n"
source_yaml_url: https://artifacts.apis.io/beatoven/eligibility/beatoven-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Beatoven.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Music
- Music Generation
- Generative Audio
- Text-to-Music
- Text To SFX
- Royalty-Free Music
- Background Music
- Video Creators
- Podcasts
- Stems
- Fairly Trained
- India
---
