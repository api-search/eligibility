---
api_specs:
- filename: edge-delta-access-api-openapi.yml
  format: yaml
  label: Edge Delta Access API
  slug: edge-delta-access-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-access-api-openapi.yml
- filename: edge-delta-add-source-api-openapi.yml
  format: yaml
  label: Edge Delta Add Source API
  slug: edge-delta-add-source-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-add-source-api-openapi.yml
- filename: edge-delta-agent-configs-api-openapi.yml
  format: yaml
  label: Edge Delta Agent Configs API
  slug: edge-delta-agent-configs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-agent-configs-api-openapi.yml
- filename: edge-delta-ai-api-openapi.yml
  format: yaml
  label: Edge Delta AI API
  slug: edge-delta-ai-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-ai-api-openapi.yml
- filename: edge-delta-event-search-api-openapi.yml
  format: yaml
  label: Edge Delta Event Search API
  slug: edge-delta-event-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-event-search-api-openapi.yml
- filename: edge-delta-get-dashboard-api-openapi.yml
  format: yaml
  label: Edge Delta Get Dashboard API
  slug: edge-delta-get-dashboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-get-dashboard-api-openapi.yml
- filename: edge-delta-get-dashboards-api-openapi.yml
  format: yaml
  label: Edge Delta Get Dashboards API
  slug: edge-delta-get-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-get-dashboards-api-openapi.yml
- filename: edge-delta-get-metrics-api-openapi.yml
  format: yaml
  label: Edge Delta Get Metrics API
  slug: edge-delta-get-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-get-metrics-api-openapi.yml
- filename: edge-delta-group-members-api-openapi.yml
  format: yaml
  label: Edge Delta Group Members API
  slug: edge-delta-group-members-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-group-members-api-openapi.yml
- filename: edge-delta-groups-api-openapi.yml
  format: yaml
  label: Edge Delta Groups API
  slug: edge-delta-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-groups-api-openapi.yml
- filename: edge-delta-integrations-api-openapi.yml
  format: yaml
  label: Edge Delta Integrations API
  slug: edge-delta-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-integrations-api-openapi.yml
- filename: edge-delta-log-search-api-openapi.yml
  format: yaml
  label: Edge Delta Log Search API
  slug: edge-delta-log-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-log-search-api-openapi.yml
- filename: edge-delta-lookup-tables-api-openapi.yml
  format: yaml
  label: Edge Delta Lookup Tables API
  slug: edge-delta-lookup-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-lookup-tables-api-openapi.yml
- filename: edge-delta-pattern-stats-api-openapi.yml
  format: yaml
  label: Edge Delta Pattern Stats API
  slug: edge-delta-pattern-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-pattern-stats-api-openapi.yml
- filename: edge-delta-pipeline-api-openapi.yml
  format: yaml
  label: Edge Delta Pipeline API
  slug: edge-delta-pipeline-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-pipeline-api-openapi.yml
- filename: edge-delta-public-api-openapi.yml
  format: yaml
  label: Edge Delta Public API
  slug: edge-delta-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-public-api-openapi.yml
- filename: edge-delta-rehydrations-api-openapi.yml
  format: yaml
  label: Edge Delta Rehydrations API
  slug: edge-delta-rehydrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-rehydrations-api-openapi.yml
- filename: edge-delta-servedbymcp-api-openapi.yml
  format: yaml
  label: Edge Delta ServedByMCP API
  slug: edge-delta-servedbymcp-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-servedbymcp-api-openapi.yml
- filename: edge-delta-users-api-openapi.yml
  format: yaml
  label: Edge Delta Users API
  slug: edge-delta-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/edge-delta/openapi/edge-delta-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: solely for Customer’s own internal business purposes
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No regulated data upload
    text: Customer will not upload any data or information that is subject to government regulation, including without limitation, protected health information regulated under the Health Insurance Portability and Accountability Act of 1996
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
name: Edge Delta
provenance_date: '2026-11-09'
provider_name: Edge Delta
provider_slug: edge-delta
slug: edge-delta-eligibility
source_date: '2026-11-09'
source_filename: edge-delta-eligibility.yml
source_heading: Eligibility
source_page: https://edgedelta.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Edge Delta\naid: edge-delta\nurl: https://edgedelta.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: solely for Customer’s own internal business purposes\nrestricted_uses:\n- summary: No regulated data upload\n  text: Customer will not upload any data or information that is subject to government regulation, including without\n    limitation, protected health information regulated under the Health Insurance Portability and Accountability\n    Act of 1996\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/edge-delta/eligibility/edge-delta-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Edge Delta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Observability
- Telemetry Pipelines
- Logging
- Metrics
- Tracing
- Monitoring
- DevOps
- SRE
- Artificial Intelligence
---
