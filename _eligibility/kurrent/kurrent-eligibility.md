---
api_specs:
- filename: kurrent-admin-api-openapi.yml
  format: yaml
  label: Kurrent Admin API
  slug: kurrent-admin-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-admin-api-openapi.yml
- filename: kurrent-gossip-api-openapi.yml
  format: yaml
  label: Kurrent Gossip API
  slug: kurrent-gossip-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-gossip-api-openapi.yml
- filename: kurrent-info-api-openapi.yml
  format: yaml
  label: Kurrent Info API
  slug: kurrent-info-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-info-api-openapi.yml
- filename: kurrent-projections-api-openapi.yml
  format: yaml
  label: Kurrent Projections API
  slug: kurrent-projections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-projections-api-openapi.yml
- filename: kurrent-statistics-api-openapi.yml
  format: yaml
  label: Kurrent Statistics API
  slug: kurrent-statistics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-statistics-api-openapi.yml
- filename: kurrent-streams-api-openapi.yml
  format: yaml
  label: Kurrent Streams API
  slug: kurrent-streams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-streams-api-openapi.yml
- filename: kurrent-subscriptions-api-openapi.yml
  format: yaml
  label: Kurrent Subscriptions API
  slug: kurrent-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-subscriptions-api-openapi.yml
- filename: kurrent-users-api-openapi.yml
  format: yaml
  label: Kurrent Users API
  slug: kurrent-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/kurrent/openapi/kurrent-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: The Site is intended for users who are at least 18 years old. If you are under the age of 18, you are not permitted to register for the Site or use the Services without parental permission.
    value: '18'
  restricted_uses:
  - summary: No commercial use of Site without approval
    text: The Site may not be used in connection with any commercial endeavors except those that are specifically endorsed or approved by us.
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
name: Kurrent
provenance_date: '2026-11-09'
provider_name: Kurrent
provider_slug: kurrent
slug: kurrent-eligibility
source_date: '2026-11-09'
source_filename: kurrent-eligibility.yml
source_heading: Eligibility
source_page: https://kurrentdb.kurrent.io/terms-of-use/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Kurrent\naid: kurrent\nurl: https://kurrentdb.kurrent.io/terms-of-use/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: No commercial use of Site without approval\n  text: The Site may not be used in connection with any commercial endeavors except those that are specifically\n    endorsed or approved by us.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old. If you are under the age of 18, you are not\n\
  \    permitted to register for the Site or use the Services without parental permission.\n"
source_yaml_url: https://artifacts.apis.io/kurrent/eligibility/kurrent-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Kurrent's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Database
- Event Sourcing
- Event Streaming
- Event-Driven Architecture
- CQRS
- Data Infrastructure
- Developer Tools
- Cloud
- Open Source
- gRPC
- AI Agents
---
