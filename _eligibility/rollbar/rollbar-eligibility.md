---
api_specs:
- filename: rollbar-webhooks-asyncapi.yml
  format: yaml
  label: Rollbar Webhooks
  slug: rollbar-webhooks
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/rollbar/asyncapi/rollbar-webhooks-asyncapi.yml
- filename: rollbar-access-tokens-api-openapi.yml
  format: yaml
  label: Rollbar Access Tokens API
  slug: rollbar-access-tokens-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-access-tokens-api-openapi.yml
- filename: rollbar-deploys-api-openapi.yml
  format: yaml
  label: Rollbar Deploys API
  slug: rollbar-deploys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-deploys-api-openapi.yml
- filename: rollbar-invites-api-openapi.yml
  format: yaml
  label: Rollbar Invites API
  slug: rollbar-invites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-invites-api-openapi.yml
- filename: rollbar-items-api-openapi.yml
  format: yaml
  label: Rollbar Items API
  slug: rollbar-items-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-items-api-openapi.yml
- filename: rollbar-items-metrics-api-openapi.yml
  format: yaml
  label: Rollbar Items Metrics API
  slug: rollbar-items-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-items-metrics-api-openapi.yml
- filename: rollbar-notifications-api-openapi.yml
  format: yaml
  label: Rollbar Notifications API
  slug: rollbar-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-notifications-api-openapi.yml
- filename: rollbar-occurrences-api-openapi.yml
  format: yaml
  label: Rollbar Occurrences API
  slug: rollbar-occurrences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-occurrences-api-openapi.yml
- filename: rollbar-occurrences-metrics-api-openapi.yml
  format: yaml
  label: Rollbar Occurrences Metrics API
  slug: rollbar-occurrences-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-occurrences-metrics-api-openapi.yml
- filename: rollbar-projects-api-openapi.yml
  format: yaml
  label: Rollbar Projects API
  slug: rollbar-projects-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-projects-api-openapi.yml
- filename: rollbar-resolution-time-metrics-api-openapi.yml
  format: yaml
  label: Rollbar Resolution Time Metrics API
  slug: rollbar-resolution-time-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-resolution-time-metrics-api-openapi.yml
- filename: rollbar-rql-jobs-api-openapi.yml
  format: yaml
  label: Rollbar RQL Jobs API
  slug: rollbar-rql-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-rql-jobs-api-openapi.yml
- filename: rollbar-source-maps-api-openapi.yml
  format: yaml
  label: Rollbar Source Maps API
  slug: rollbar-source-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-source-maps-api-openapi.yml
- filename: rollbar-teams-api-openapi.yml
  format: yaml
  label: Rollbar Teams API
  slug: rollbar-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-teams-api-openapi.yml
- filename: rollbar-users-api-openapi.yml
  format: yaml
  label: Rollbar Users API
  slug: rollbar-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/rollbar/openapi/rollbar-users-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The Services are controlled and operated from facilities in the United States in the state of California. You may not use the Services if you are a resident of a country embargoed by the United States
  entity_types:
  - text: You must be a human to create a User Account.
    type: individual
  minimum_age:
    text: You must be age 18 or older.
    value: '18'
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
name: Rollbar
provenance_date: '2026-11-10'
provider_name: Rollbar
provider_slug: rollbar
slug: rollbar-eligibility
source_date: '2026-11-10'
source_filename: rollbar-eligibility.yml
source_heading: Eligibility
source_page: https://docs.rollbar.com/docs/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Rollbar\naid: rollbar\nurl: https://docs.rollbar.com/docs/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The Services are controlled and operated from facilities in the United States in the state of California.\n    You may not use the Services if you are a resident of a country embargoed by the United States\nentity_types:\n- type: individual\n  text: You must be a human to create a User Account.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be age 18 or older.\n"
source_yaml_url: https://artifacts.apis.io/rollbar/eligibility/rollbar-eligibility.yml
stated_fields:
- countries
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from Rollbar's own page on 2026-11-10.
synthetic: false
tags:
- Error Tracking
- Monitoring
- Debugging
- DevOps
- Application Performance
- Developer Tools
---
