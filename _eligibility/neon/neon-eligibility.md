---
api_specs:
- filename: neon-auth-webhooks-asyncapi.yml
  format: yaml
  label: Neon Auth
  slug: auth
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/neon/asyncapi/neon-auth-webhooks-asyncapi.yml
- filename: neon-api-keys-api-openapi.yml
  format: yaml
  label: Neon API Keys API
  slug: neon-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-api-keys-api-openapi.yml
- filename: neon-auth-api-openapi.yml
  format: yaml
  label: Neon Auth API
  slug: neon-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-auth-api-openapi.yml
- filename: neon-branches-api-openapi.yml
  format: yaml
  label: Neon Branches API
  slug: neon-branches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-branches-api-openapi.yml
- filename: neon-consumption-api-openapi.yml
  format: yaml
  label: Neon Consumption API
  slug: neon-consumption-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-consumption-api-openapi.yml
- filename: neon-data-api-api-openapi.yml
  format: yaml
  label: Neon Data API
  slug: neon-data-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-data-api-api-openapi.yml
- filename: neon-databases-api-openapi.yml
  format: yaml
  label: Neon Databases API
  slug: neon-databases-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-databases-api-openapi.yml
- filename: neon-endpoints-api-openapi.yml
  format: yaml
  label: Neon Endpoints API
  slug: neon-endpoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-endpoints-api-openapi.yml
- filename: neon-operations-api-openapi.yml
  format: yaml
  label: Neon Operations API
  slug: neon-operations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-operations-api-openapi.yml
- filename: neon-projects-api-openapi.yml
  format: yaml
  label: Neon Projects API
  slug: neon-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-projects-api-openapi.yml
- filename: neon-roles-api-openapi.yml
  format: yaml
  label: Neon Roles API
  slug: neon-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/neon/openapi/neon-roles-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are entering into this Schedule on behalf of a company (such as your employer) or other legal entity, you represent and warrant that you are authorized to bind that entity to this Schedule
    type: business
  - text: otherwise, "Customer" refers to you as an individual
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
name: Neon
provenance_date: '2026-11-10'
provider_name: Neon
provider_slug: neon
slug: neon-eligibility
source_date: '2026-11-10'
source_filename: neon-eligibility.yml
source_heading: Eligibility
source_page: https://neon.com/platform-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Neon\naid: neon\nurl: https://neon.com/platform-terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are entering into this Schedule on behalf of a company (such as your employer) or other legal entity,\n    you represent and warrant that you are authorized to bind that entity to this Schedule\n- type: individual\n  text: otherwise, \"Customer\" refers to you as an individual\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/neon/eligibility/neon-eligibility.yml
stated_fields:
- entity_types
summary_line: 2 quoted statements, read from Neon's own page on 2026-11-10.
synthetic: false
tags:
- Database
- Serverless
- PostgreSQL
- Infrastructure
- Authentication
- Edge
---
