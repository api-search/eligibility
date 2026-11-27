---
api_specs:
- filename: hyperdx-alerts-api-openapi.yml
  format: yaml
  label: HyperDX Alerts API
  slug: hyperdx-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-alerts-api-openapi.yml
- filename: hyperdx-charts-api-openapi.yml
  format: yaml
  label: HyperDX Charts API
  slug: hyperdx-charts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-charts-api-openapi.yml
- filename: hyperdx-connections-api-openapi.yml
  format: yaml
  label: HyperDX Connections API
  slug: hyperdx-connections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-connections-api-openapi.yml
- filename: hyperdx-dashboards-api-openapi.yml
  format: yaml
  label: HyperDX Dashboards API
  slug: hyperdx-dashboards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-dashboards-api-openapi.yml
- filename: hyperdx-saved-searches-api-openapi.yml
  format: yaml
  label: HyperDX Saved Searches API
  slug: hyperdx-saved-searches-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-saved-searches-api-openapi.yml
- filename: hyperdx-search-api-openapi.yml
  format: yaml
  label: HyperDX Search API
  slug: hyperdx-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-search-api-openapi.yml
- filename: hyperdx-sources-api-openapi.yml
  format: yaml
  label: HyperDX Sources API
  slug: hyperdx-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-sources-api-openapi.yml
- filename: hyperdx-team-api-openapi.yml
  format: yaml
  label: HyperDX Team API
  slug: hyperdx-team-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-team-api-openapi.yml
- filename: hyperdx-webhooks-api-openapi.yml
  format: yaml
  label: HyperDX Webhooks API
  slug: hyperdx-webhooks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/hyperdx/openapi/hyperdx-webhooks-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: IF YOU ACCESS OR USE THE HYPERDX SERVICE ON BEHALF OF AN ENTITY, YOU HEREBY REPRESENT AND WARRANT TO DEPLOYSENTINEL THAT YOU HAVE THE ACTUAL AUTHORITY TO BIND SUCH ENTITY TO THE AGREEMENT.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Protected health information
    text: use the HyperDX Service to process any protected health information (as defined by the Health Insurance Portability and Accountability Act of 1996) without first entering into a BAA with DeploySentinel;
  - summary: Classified or ITAR data
    text: use the HyperDX Service to store or process any classified information
  - summary: High-risk activities
    text: use the HyperDX Service for High Risk Activities, or
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
name: HyperDX
provenance_date: '2026-11-09'
provider_name: HyperDX
provider_slug: hyperdx
slug: hyperdx-eligibility
source_date: '2026-11-09'
source_filename: hyperdx-eligibility.yml
source_heading: Eligibility
source_page: https://www.hyperdx.io/terms/service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: HyperDX\naid: hyperdx\nurl: https://www.hyperdx.io/terms/service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: IF YOU ACCESS OR USE THE HYPERDX SERVICE ON BEHALF OF AN ENTITY, YOU HEREBY REPRESENT AND WARRANT TO DEPLOYSENTINEL\n    THAT YOU HAVE THE ACTUAL AUTHORITY TO BIND SUCH ENTITY TO THE AGREEMENT.\nrestricted_uses:\n- summary: Protected health information\n  text: use the HyperDX Service to process any protected health information (as defined by the Health Insurance\n    Portability and Accountability Act of 1996) without first\
  \ entering into a BAA with DeploySentinel;\n- summary: Classified or ITAR data\n  text: use the HyperDX Service to store or process any classified information\n- summary: High-risk activities\n  text: use the HyperDX Service for High Risk Activities, or\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/hyperdx/eligibility/hyperdx-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from HyperDX's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Observability
- Monitoring
- Logging
- Tracing
- Metrics
- OpenTelemetry
- ClickHouse
- Open Source
- Alerting
- Dashboards
- Session Replay
- Developer Tools
- Agents
---
