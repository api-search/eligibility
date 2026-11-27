---
api_specs:
- filename: blue-prism-calendars-api-openapi.yml
  format: yaml
  label: Blue Prism Calendars API
  slug: blue-prism-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-calendars-api-openapi.yml
- filename: blue-prism-dashboards-api-openapi.yml
  format: yaml
  label: Blue Prism Dashboards API
  slug: blue-prism-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-dashboards-api-openapi.yml
- filename: blue-prism-encryption-schemes-api-openapi.yml
  format: yaml
  label: Blue Prism Encryption Schemes API
  slug: blue-prism-encryption-schemes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-encryption-schemes-api-openapi.yml
- filename: blue-prism-environment-variables-api-openapi.yml
  format: yaml
  label: Blue Prism Environment Variables API
  slug: blue-prism-environment-variables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-environment-variables-api-openapi.yml
- filename: blue-prism-health-api-openapi.yml
  format: yaml
  label: Blue Prism Health API
  slug: blue-prism-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-health-api-openapi.yml
- filename: blue-prism-licenses-api-openapi.yml
  format: yaml
  label: Blue Prism Licenses API
  slug: blue-prism-licenses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-licenses-api-openapi.yml
- filename: blue-prism-pools-api-openapi.yml
  format: yaml
  label: Blue Prism Pools API
  slug: blue-prism-pools-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-pools-api-openapi.yml
- filename: blue-prism-processes-api-openapi.yml
  format: yaml
  label: Blue Prism Processes API
  slug: blue-prism-processes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-processes-api-openapi.yml
- filename: blue-prism-resources-api-openapi.yml
  format: yaml
  label: Blue Prism Resources API
  slug: blue-prism-resources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-resources-api-openapi.yml
- filename: blue-prism-schedulelogs-api-openapi.yml
  format: yaml
  label: Blue Prism Schedule Logs API
  slug: blue-prism-schedulelogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-schedulelogs-api-openapi.yml
- filename: blue-prism-schedules-api-openapi.yml
  format: yaml
  label: Blue Prism Schedules API
  slug: blue-prism-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-schedules-api-openapi.yml
- filename: blue-prism-sessions-api-openapi.yml
  format: yaml
  label: Blue Prism Sessions API
  slug: blue-prism-sessions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-sessions-api-openapi.yml
- filename: blue-prism-subscriptions-api-openapi.yml
  format: yaml
  label: Blue Prism Subscriptions API
  slug: blue-prism-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-subscriptions-api-openapi.yml
- filename: blue-prism-user-api-openapi.yml
  format: yaml
  label: Blue Prism User API
  slug: blue-prism-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-user-api-openapi.yml
- filename: blue-prism-work-queue-groups-api-openapi.yml
  format: yaml
  label: Blue Prism Work Queue Groups API
  slug: blue-prism-work-queue-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-work-queue-groups-api-openapi.yml
- filename: blue-prism-work-queues-api-openapi.yml
  format: yaml
  label: Blue Prism Work Queues API
  slug: blue-prism-work-queues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-work-queues-api-openapi.yml
- filename: blue-prism-timezones-api-openapi.yml
  format: yaml
  label: Blue Prism Timezones API
  slug: blue-prism-timezones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/blue-prism/openapi/blue-prism-timezones-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: FOR THIS PURPOSE “YOU” INCLUDES THE COMPANY THAT EMPLOYS YOU.
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
name: Blue Prism
provenance_date: '2026-11-09'
provider_name: Blue Prism
provider_slug: blue-prism
slug: blue-prism-eligibility
source_date: '2026-11-09'
source_filename: blue-prism-eligibility.yml
source_heading: Eligibility
source_page: https://www.blueprism.com/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Blue Prism\naid: blue-prism\nurl: https://www.blueprism.com/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: FOR THIS PURPOSE “YOU” INCLUDES THE COMPANY THAT EMPLOYS YOU.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/blue-prism/eligibility/blue-prism-eligibility.yml
stated_fields:
- entity_types
summary_line: 1 quoted statement, read from Blue Prism's own page on 2026-11-09.
synthetic: false
tags:
- AI Automation
- RPA
- Intelligent Automation
- Business Process Management
- Process Orchestration
- AI Agents
- Workflow Automation
- Enterprise Software
---
