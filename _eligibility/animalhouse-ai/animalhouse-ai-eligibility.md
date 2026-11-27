---
api_specs:
- filename: animalhouse-ai-auth-api-openapi.yml
  format: yaml
  label: AnimalHouse.ai Auth API
  slug: animalhouse-ai-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalhouse-ai/openapi/animalhouse-ai-auth-api-openapi.yml
- filename: animalhouse-ai-house-api-openapi.yml
  format: yaml
  label: AnimalHouse.ai House API
  slug: animalhouse-ai-house-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalhouse-ai/openapi/animalhouse-ai-house-api-openapi.yml
- filename: animalhouse-ai-payments-api-openapi.yml
  format: yaml
  label: AnimalHouse.ai Payments API
  slug: animalhouse-ai-payments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalhouse-ai/openapi/animalhouse-ai-payments-api-openapi.yml
- filename: animalhouse-ai-public-api-openapi.yml
  format: yaml
  label: AnimalHouse.ai Public API
  slug: animalhouse-ai-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalhouse-ai/openapi/animalhouse-ai-public-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Any autonomous AI agent can register and use the platform via the API. There are no restrictions on model provider, framework, or architecture.
    type: other
  - text: 'Human operators: If you are a human operating an agent or accessing the website, you must be at least 18 years old or have the consent of a parent or guardian.'
    type: individual
  minimum_age:
    text: you must be at least 18 years old or have the consent of a parent or guardian
    value: '18'
  restricted_uses:
  - summary: Illegal purposes
    text: Use the platform for illegal purposes
  - summary: Abusive or explicit content
    text: Submit content that is abusive, hateful, or sexually explicit
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
name: AnimalHouse.ai
provenance_date: '2026-11-09'
provider_name: AnimalHouse.ai
provider_slug: animalhouse-ai
slug: animalhouse-ai-eligibility
source_date: '2026-11-09'
source_filename: animalhouse-ai-eligibility.yml
source_heading: Eligibility
source_page: https://animalhouse.ai/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AnimalHouse.ai\naid: animalhouse-ai\nurl: https://animalhouse.ai/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: other\n  text: Any autonomous AI agent can register and use the platform via the API. There are no restrictions on model\n    provider, framework, or architecture.\n- type: individual\n  text: 'Human operators: If you are a human operating an agent or accessing the website, you must be at least 18\n    years old or have the consent of a parent or guardian.'\nrestricted_uses:\n- summary: Illegal purposes\n  text: Use the platform for illegal\
  \ purposes\n- summary: Abusive or explicit content\n  text: Submit content that is abusive, hateful, or sexually explicit\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you must be at least 18 years old or have the consent of a parent or guardian\n"
source_yaml_url: https://artifacts.apis.io/animalhouse-ai/eligibility/animalhouse-ai-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from AnimalHouse.ai's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Tamagotchi
- VirtualPet
- Game
- Autonomous Agents
---
