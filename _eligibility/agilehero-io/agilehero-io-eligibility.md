---
api_specs:
- filename: agilehero-io-account-api-openapi.yml
  format: yaml
  label: AgileHero Account API
  slug: agilehero-io-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-account-api-openapi.yml
- filename: agilehero-io-cards-api-openapi.yml
  format: yaml
  label: AgileHero Cards API
  slug: agilehero-io-cards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-cards-api-openapi.yml
- filename: agilehero-io-discovery-api-openapi.yml
  format: yaml
  label: AgileHero Discovery API
  slug: agilehero-io-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-discovery-api-openapi.yml
- filename: agilehero-io-projects-api-openapi.yml
  format: yaml
  label: AgileHero Projects API
  slug: agilehero-io-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-projects-api-openapi.yml
- filename: agilehero-io-webhooks-api-openapi.yml
  format: yaml
  label: AgileHero Webhooks API
  slug: agilehero-io-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/agilehero-io/openapi/agilehero-io-webhooks-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: a natural person with full capacity to perform acts in law
    type: individual
  - text: a legal person, or an organisational entity who uses AgileHero
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal content
    text: Each User is prohibited from providing Content of unlawful nature
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
name: AgileHero
provenance_date: '2026-11-09'
provider_name: AgileHero
provider_slug: agilehero-io
slug: agilehero-io-eligibility
source_date: '2026-11-09'
source_filename: agilehero-io-eligibility.yml
source_heading: Eligibility
source_page: https://agilehero.io/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AgileHero\naid: agilehero-io\nurl: https://agilehero.io/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: a natural person with full capacity to perform acts in law\n- type: business\n  text: a legal person, or an organisational entity who uses AgileHero\nrestricted_uses:\n- summary: Illegal content\n  text: Each User is prohibited from providing Content of unlawful nature\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/agilehero-io/eligibility/agilehero-io-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from AgileHero's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Project Management
- Agile
- AI Integration
- Collaboration
---
