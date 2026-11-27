---
api_specs:
- filename: raygun-applications-api-openapi.yml
  format: yaml
  label: Raygun Applications API
  slug: raygun-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-applications-api-openapi.yml
- filename: raygun-errors-api-openapi.yml
  format: yaml
  label: Raygun Errors API
  slug: raygun-errors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-errors-api-openapi.yml
- filename: raygun-deployments-api-openapi.yml
  format: yaml
  label: Raygun Deployments API
  slug: raygun-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-deployments-api-openapi.yml
- filename: raygun-source-maps-api-openapi.yml
  format: yaml
  label: Raygun Source Maps API
  slug: raygun-source-maps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-source-maps-api-openapi.yml
- filename: raygun-sessions-api-openapi.yml
  format: yaml
  label: Raygun Sessions API
  slug: raygun-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-sessions-api-openapi.yml
- filename: raygun-pages-api-openapi.yml
  format: yaml
  label: Raygun Pages API
  slug: raygun-pages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-pages-api-openapi.yml
- filename: raygun-customers-api-openapi.yml
  format: yaml
  label: Raygun Customers API
  slug: raygun-customers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-customers-api-openapi.yml
- filename: raygun-metrics-api-openapi.yml
  format: yaml
  label: Raygun Metrics API
  slug: raygun-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-metrics-api-openapi.yml
- filename: raygun-flutter-symbols-api-openapi.yml
  format: yaml
  label: Raygun Flutter Symbols API
  slug: raygun-flutter-symbols-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-flutter-symbols-api-openapi.yml
- filename: raygun-teams-api-openapi.yml
  format: yaml
  label: Raygun Teams API
  slug: raygun-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-teams-api-openapi.yml
- filename: raygun-invitations-api-openapi.yml
  format: yaml
  label: Raygun Invitations API
  slug: raygun-invitations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-invitations-api-openapi.yml
- filename: raygun-plans-api-openapi.yml
  format: yaml
  label: Raygun Plans API
  slug: raygun-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-plans-api-openapi.yml
- filename: raygun-webhooks-asyncapi.yml
  format: yaml
  label: Raygun Outbound Webhooks
  slug: raygun-webhooks-api
  spec_type: AsyncAPI
  url: https://artifacts.apis.io/raygun/openapi/raygun-webhooks-asyncapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: if You are an individual, You are 18 years of age or older, and are a human, and not a computer service or automated “bot”
    type: individual
  - text: if You are an entity, You are authorized to use the Service and agree to these Terms of Service
    type: business
  minimum_age:
    text: if You are an individual, You are 18 years of age or older
    value: '18'
  restricted_uses:
  - summary: Lawful purposes only
    text: You will use the Service only for lawful purposes. You must not use the Service to violate any laws in Your jurisdiction, including but not limited to any copyright laws.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You have provided accurate and valid information at the time requested during the registration process.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Raygun
provenance_date: '2026-11-10'
provider_name: Raygun
provider_slug: raygun
slug: raygun-eligibility
source_date: '2026-11-10'
source_filename: raygun-eligibility.yml
source_heading: Eligibility
source_page: https://raygun.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Raygun\naid: raygun\nurl: https://raygun.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: if You are an individual, You are 18 years of age or older, and are a human, and not a computer service\n    or automated “bot”\n- type: business\n  text: if You are an entity, You are authorized to use the Service and agree to these Terms of Service\nrestricted_uses:\n- summary: Lawful purposes only\n  text: You will use the Service only for lawful purposes. You must not use the Service to violate any laws in Your\n    jurisdiction,\
  \ including but not limited to any copyright laws.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You have provided accurate and valid information at the time requested during the registration process.\nminimum_age:\n  value: '18'\n  text: if You are an individual, You are 18 years of age or older\n"
source_yaml_url: https://artifacts.apis.io/raygun/eligibility/raygun-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from Raygun's own page on 2026-11-10.
synthetic: false
tags:
- Observability
- Crash Reporting
- Real User Monitoring
- Application Performance Monitoring
- Error Tracking
- Errors
- Monitoring
- DevOps
- Source Maps
- Deployment
---
