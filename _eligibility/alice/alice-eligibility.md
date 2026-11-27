---
api_specs:
- filename: alice-api-keys-api-openapi.yml
  format: yaml
  label: Alice api keys API
  slug: alice-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alice/openapi/alice-api-keys-api-openapi.yml
- filename: alice-collection-api-openapi.yml
  format: yaml
  label: Alice Collection API
  slug: alice-collection-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alice/openapi/alice-collection-api-openapi.yml
- filename: alice-content-api-openapi.yml
  format: yaml
  label: Alice Content API
  slug: alice-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alice/openapi/alice-content-api-openapi.yml
- filename: alice-flags-api-openapi.yml
  format: yaml
  label: Alice Flags API
  slug: alice-flags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alice/openapi/alice-flags-api-openapi.yml
- filename: alice-users-api-openapi.yml
  format: yaml
  label: Alice Users API
  slug: alice-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alice/openapi/alice-users-api-openapi.yml
- filename: alice-wonderbuild-api-openapi.yml
  format: yaml
  label: Alice WonderBuild API
  slug: alice-wonderbuild-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alice/openapi/alice-wonderbuild-api-openapi.yml
- filename: alice-wonderfence-api-openapi.yml
  format: yaml
  label: Alice WonderFence API
  slug: alice-wonderfence-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/alice/openapi/alice-wonderfence-api-openapi.yml
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
name: Alice
provenance_date: '2026-11-09'
provider_name: Alice
provider_slug: alice
slug: alice-eligibility
source_date: '2026-11-09'
source_filename: alice-eligibility.yml
source_heading: Eligibility
source_page: https://alice.io/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Alice\naid: alice\nurl: https://alice.io/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: The Site is only intended for individuals aged sixteen (16) years or older.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: The Site is only intended for individuals aged sixteen (16) years or older.\n"
source_yaml_url: https://artifacts.apis.io/alice/eligibility/alice-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Alice's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- AI Security
- AI Safety
- Content Moderation
- Trust and Safety
- LLM Guardrails
- Red Teaming
- Generative AI
---
