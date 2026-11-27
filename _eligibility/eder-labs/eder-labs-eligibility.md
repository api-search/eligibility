---
api_specs:
- filename: eder-labs-ingestion-api-openapi.yml
  format: yaml
  label: Eder Labs Ingestion API
  slug: eder-labs-ingestion-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eder-labs/openapi/eder-labs-ingestion-api-openapi.yml
- filename: eder-labs-meta-api-openapi.yml
  format: yaml
  label: Eder Labs Meta API
  slug: eder-labs-meta-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eder-labs/openapi/eder-labs-meta-api-openapi.yml
- filename: eder-labs-query-api-openapi.yml
  format: yaml
  label: Eder Labs Query API
  slug: eder-labs-query-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eder-labs/openapi/eder-labs-query-api-openapi.yml
- filename: eder-labs-users-api-openapi.yml
  format: yaml
  label: Eder Labs Users API
  slug: eder-labs-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/eder-labs/openapi/eder-labs-users-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '"You" refers both to you as an individual and the entity you represent.'
    type: individual
  minimum_age:
    text: null
    value: null
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
name: Eder Labs
provenance_date: '2026-11-09'
provider_name: Eder Labs
provider_slug: eder-labs
slug: eder-labs-eligibility
source_date: '2026-11-09'
source_filename: eder-labs-eligibility.yml
source_heading: Eligibility
source_page: https://www.eder.io/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Eder Labs\naid: eder-labs\nurl: https://www.eder.io/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '\"You\" refers both to you as an individual and the entity you represent.'\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/eder-labs/eligibility/eder-labs-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Eder Labs's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Cloud Saas
- AI Agents
- Memory
- Knowledge Graph
- Personalization
- Privacy
- Open Source
- Developer Tools
- RAG
---
