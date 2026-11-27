---
api_specs:
- filename: activefence-api-keys-api-openapi.yml
  format: yaml
  label: ActiveFence api keys API
  slug: activefence-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activefence/openapi/activefence-api-keys-api-openapi.yml
- filename: activefence-collection-api-openapi.yml
  format: yaml
  label: ActiveFence Collection API
  slug: activefence-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activefence/openapi/activefence-collection-api-openapi.yml
- filename: activefence-content-api-openapi.yml
  format: yaml
  label: ActiveFence Content API
  slug: activefence-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activefence/openapi/activefence-content-api-openapi.yml
- filename: activefence-flags-api-openapi.yml
  format: yaml
  label: ActiveFence Flags API
  slug: activefence-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activefence/openapi/activefence-flags-api-openapi.yml
- filename: activefence-users-api-openapi.yml
  format: yaml
  label: ActiveFence Users API
  slug: activefence-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activefence/openapi/activefence-users-api-openapi.yml
- filename: activefence-wonderbuild-api-openapi.yml
  format: yaml
  label: ActiveFence Wonder Build API
  slug: activefence-wonderbuild-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activefence/openapi/activefence-wonderbuild-api-openapi.yml
- filename: activefence-wonderfence-api-openapi.yml
  format: yaml
  label: ActiveFence Wonder Fence API
  slug: activefence-wonderfence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/activefence/openapi/activefence-wonderfence-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: The Site is only intended for individuals aged sixteen (16) years or older.
    type: individual
  minimum_age:
    text: The Site is only intended for individuals aged sixteen (16) years or older.
    value: '16'
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
name: ActiveFence
provenance_date: '2026-11-09'
provider_name: ActiveFence
provider_slug: activefence
slug: activefence-eligibility
source_date: '2026-11-09'
source_filename: activefence-eligibility.yml
source_heading: Eligibility
source_page: https://alice.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: ActiveFence\naid: activefence\nurl: https://alice.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged sixteen (16) years or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Site is only intended for individuals aged sixteen (16) years or older.\n"
source_yaml_url: https://artifacts.apis.io/activefence/eligibility/activefence-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from ActiveFence's own page on 2026-11-09.
synthetic: false
tags:
- AI Safety
- AI Security
- Trust and Safety
- Content Moderation
- Guardrails
- Red Teaming
- LLM Security
- Prompt Injection
- AI Governance
- Risk Scoring
- User Generated Content
- Child Safety
---
