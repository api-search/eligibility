---
api_specs:
- filename: moesif-applications-api-openapi.yml
  format: yaml
  label: Moesif Applications API
  slug: moesif-applications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-applications-api-openapi.yml
- filename: moesif-balance-transactions-api-openapi.yml
  format: yaml
  label: Moesif Balance Transactions API
  slug: moesif-balance-transactions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-balance-transactions-api-openapi.yml
- filename: moesif-billing-meters-api-openapi.yml
  format: yaml
  label: Moesif Billing Meters API
  slug: moesif-billing-meters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-billing-meters-api-openapi.yml
- filename: moesif-billing-reports-api-openapi.yml
  format: yaml
  label: Moesif Billing Reports API
  slug: moesif-billing-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-billing-reports-api-openapi.yml
- filename: moesif-cohorts-api-openapi.yml
  format: yaml
  label: Moesif Cohorts API
  slug: moesif-cohorts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-cohorts-api-openapi.yml
- filename: moesif-companies-api-openapi.yml
  format: yaml
  label: Moesif Companies API
  slug: moesif-companies-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-companies-api-openapi.yml
- filename: moesif-dashboards-api-openapi.yml
  format: yaml
  label: Moesif Dashboards API
  slug: moesif-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-dashboards-api-openapi.yml
- filename: moesif-email-templates-api-openapi.yml
  format: yaml
  label: Moesif Email Templates API
  slug: moesif-email-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-email-templates-api-openapi.yml
- filename: moesif-governance-rules-api-openapi.yml
  format: yaml
  label: Moesif Governance Rules API
  slug: moesif-governance-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-governance-rules-api-openapi.yml
- filename: moesif-metrics-api-openapi.yml
  format: yaml
  label: Moesif Metrics API
  slug: moesif-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-metrics-api-openapi.yml
- filename: moesif-product-catalog-api-openapi.yml
  format: yaml
  label: Moesif Product Catalog API
  slug: moesif-product-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-product-catalog-api-openapi.yml
- filename: moesif-properties-api-openapi.yml
  format: yaml
  label: Moesif Properties API
  slug: moesif-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-properties-api-openapi.yml
- filename: moesif-subscriptions-api-openapi.yml
  format: yaml
  label: Moesif Subscriptions API
  slug: moesif-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-subscriptions-api-openapi.yml
- filename: moesif-users-api-openapi.yml
  format: yaml
  label: Moesif Users API
  slug: moesif-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-users-api-openapi.yml
- filename: moesif-workspaces-api-openapi.yml
  format: yaml
  label: Moesif Workspaces API
  slug: moesif-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/moesif/openapi/moesif-workspaces-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are a resident of a country embargoed by the United States, or are a foreign person or entity blocked or denied by the United State government.
  entity_types:
  - text: if you are using the Services on behalf of a company or other such legal entity, you represent that you have the authority to bind such entity to these Terms
    type: business
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
name: Moesif
provenance_date: '2026-11-10'
provider_name: Moesif
provider_slug: moesif
slug: moesif-eligibility
source_date: '2026-11-10'
source_filename: moesif-eligibility.yml
source_heading: Eligibility
source_page: https://www.moesif.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Moesif\naid: moesif\nurl: https://www.moesif.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are a resident of a country embargoed by the United States, or are a\n    foreign person or entity blocked or denied by the United State government.\nentity_types:\n- type: business\n  text: if you are using the Services on behalf of a company or other such legal entity, you represent that you\n    have the authority to bind such entity to these Terms\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/moesif/eligibility/moesif-eligibility.yml
stated_fields:
- countries
- entity_types
summary_line: 2 quoted statements, read from Moesif's own page on 2026-11-10.
synthetic: false
tags:
- Analytics
- Monitoring
- Monetization
- Governance
- Observability
- Billing
- AI Agents
- LLM Analytics
- OpenTelemetry
- Developer Portal
- Platform
- Insights
- Developer Tools
---
