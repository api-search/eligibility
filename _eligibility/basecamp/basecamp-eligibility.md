---
api_specs:
- filename: basecamp-webhooks-asyncapi.yml
  format: yaml
  label: Basecamp Webhooks
  slug: basecamp-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/basecamp/asyncapi/basecamp-webhooks-asyncapi.yml
- filename: basecamp-authorization-api-openapi.yml
  format: yaml
  label: Basecamp Authorization API
  slug: basecamp-authorization-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-authorization-api-openapi.yml
- filename: basecamp-campfires-api-openapi.yml
  format: yaml
  label: Basecamp Campfires API
  slug: basecamp-campfires-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-campfires-api-openapi.yml
- filename: basecamp-card-tables-api-openapi.yml
  format: yaml
  label: Basecamp Card Tables API
  slug: basecamp-card-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-card-tables-api-openapi.yml
- filename: basecamp-comments-api-openapi.yml
  format: yaml
  label: Basecamp Comments API
  slug: basecamp-comments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-comments-api-openapi.yml
- filename: basecamp-documents-api-openapi.yml
  format: yaml
  label: Basecamp Documents API
  slug: basecamp-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-documents-api-openapi.yml
- filename: basecamp-identity-api-openapi.yml
  format: yaml
  label: Basecamp Identity API
  slug: basecamp-identity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-identity-api-openapi.yml
- filename: basecamp-messages-api-openapi.yml
  format: yaml
  label: Basecamp Messages API
  slug: basecamp-messages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-messages-api-openapi.yml
- filename: basecamp-people-api-openapi.yml
  format: yaml
  label: Basecamp People API
  slug: basecamp-people-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-people-api-openapi.yml
- filename: basecamp-projects-api-openapi.yml
  format: yaml
  label: Basecamp Projects API
  slug: basecamp-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-projects-api-openapi.yml
- filename: basecamp-recordings-api-openapi.yml
  format: yaml
  label: Basecamp Recordings API
  slug: basecamp-recordings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-recordings-api-openapi.yml
- filename: basecamp-schedule-entries-api-openapi.yml
  format: yaml
  label: Basecamp Schedule Entries API
  slug: basecamp-schedule-entries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-schedule-entries-api-openapi.yml
- filename: basecamp-schedules-api-openapi.yml
  format: yaml
  label: Basecamp Schedules API
  slug: basecamp-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-schedules-api-openapi.yml
- filename: basecamp-subscriptions-api-openapi.yml
  format: yaml
  label: Basecamp Subscriptions API
  slug: basecamp-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-subscriptions-api-openapi.yml
- filename: basecamp-templates-api-openapi.yml
  format: yaml
  label: Basecamp Templates API
  slug: basecamp-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-templates-api-openapi.yml
- filename: basecamp-to-do-lists-api-openapi.yml
  format: yaml
  label: Basecamp To-Do Lists API
  slug: basecamp-to-do-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-to-do-lists-api-openapi.yml
- filename: basecamp-to-dos-api-openapi.yml
  format: yaml
  label: Basecamp To-Dos API
  slug: basecamp-to-dos-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-to-dos-api-openapi.yml
- filename: basecamp-token-api-openapi.yml
  format: yaml
  label: Basecamp Token API
  slug: basecamp-token-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-token-api-openapi.yml
- filename: basecamp-uploads-api-openapi.yml
  format: yaml
  label: Basecamp Uploads API
  slug: basecamp-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-uploads-api-openapi.yml
- filename: basecamp-webhooks-api-openapi.yml
  format: yaml
  label: Basecamp Webhooks API
  slug: basecamp-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/basecamp/openapi/basecamp-webhooks-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: “you” or “your” refers to the people or organizations that own an account with one or more of our Services.
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
name: Basecamp
provenance_date: '2026-11-09'
provider_name: Basecamp
provider_slug: basecamp
slug: basecamp-eligibility
source_date: '2026-11-09'
source_filename: basecamp-eligibility.yml
source_heading: Eligibility
source_page: https://37signals.com/policies/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Basecamp\naid: basecamp\nurl: https://37signals.com/policies/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: “you” or “your” refers to the people or organizations that own an account with one or more of our Services.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/basecamp/eligibility/basecamp-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Basecamp's own page on 2026-11-09.
synthetic: false
tags:
- Collaboration
- Project Management
- REST
- Software-as-a-Service
- Team Communication
---
