---
api_specs:
- filename: inngest-account-api-openapi.yml
  format: yaml
  label: Inngest Account API
  slug: inngest-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-account-api-openapi.yml
- filename: inngest-apps-api-openapi.yml
  format: yaml
  label: Inngest Apps API
  slug: inngest-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-apps-api-openapi.yml
- filename: inngest-environments-api-openapi.yml
  format: yaml
  label: Inngest Environments API
  slug: inngest-environments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-environments-api-openapi.yml
- filename: inngest-events-api-openapi.yml
  format: yaml
  label: Inngest Events API
  slug: inngest-events-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-events-api-openapi.yml
- filename: inngest-functions-api-openapi.yml
  format: yaml
  label: Inngest Functions API
  slug: inngest-functions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-functions-api-openapi.yml
- filename: inngest-keys-api-openapi.yml
  format: yaml
  label: Inngest Keys API
  slug: inngest-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-keys-api-openapi.yml
- filename: inngest-runs-api-openapi.yml
  format: yaml
  label: Inngest Runs API
  slug: inngest-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-runs-api-openapi.yml
- filename: inngest-webhooks-api-openapi.yml
  format: yaml
  label: Inngest Webhooks API
  slug: inngest-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-webhooks-api-openapi.yml
- filename: inngest-experiments-api-openapi.yml
  format: yaml
  label: Inngest Experiments API
  slug: inngest-experiments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-experiments-api-openapi.yml
- filename: inngest-insights-api-openapi.yml
  format: yaml
  label: Inngest Insights API
  slug: inngest-insights-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-insights-api-openapi.yml
- filename: inngest-partner-api-api-openapi.yml
  format: yaml
  label: Inngest Partner API
  slug: inngest-partner-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-partner-api-api-openapi.yml
- filename: inngest-sandboxes-api-openapi.yml
  format: yaml
  label: Inngest Sandboxes API
  slug: inngest-sandboxes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-sandboxes-api-openapi.yml
- filename: inngest-sessions-api-openapi.yml
  format: yaml
  label: Inngest Sessions API
  slug: inngest-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/inngest/openapi/inngest-sessions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: There are no restrictions for Users in terms of being Consumers or Business Users
    type: business
  - text: Users who are European Consumers are granted a statutory cancellation right under EU rules
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial promotion
    text: Commercial use restrictions registering or using this Application in order to promote, sell or advertise products or services of any kind in any way
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
name: Inngest
provenance_date: '2026-11-09'
provider_name: Inngest
provider_slug: inngest
slug: inngest-eligibility
source_date: '2026-11-09'
source_filename: inngest-eligibility.yml
source_heading: Eligibility
source_page: https://www.inngest.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Inngest\naid: inngest\nurl: https://www.inngest.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: There are no restrictions for Users in terms of being Consumers or Business Users\n- type: individual\n  text: Users who are European Consumers are granted a statutory cancellation right under EU rules\nrestricted_uses:\n- summary: Commercial promotion\n  text: Commercial use restrictions registering or using this Application in order to promote, sell or advertise\n    products or services of any kind in any way\nverification:\n\
  \  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/inngest/eligibility/inngest-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 3 quoted statements, read from Inngest's own page on 2026-11-09.
synthetic: false
tags:
- AI Agents
- AgentKit
- Background Jobs
- Connect
- Cron Jobs
- Dev Server
- Durable Endpoints
- Durable Execution
- Event-Driven
- Insights
- Orchestration
- Queues
- Real-Time
- Self-Hosting
- Serverless
- Signals
- Step Functions
- Webhook
- Workflows
---
