---
api_specs:
- filename: lightup-api-credentials-api-openapi.yml
  format: yaml
  label: Lightup API Credentials API
  slug: lightup-api-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-api-credentials-api-openapi.yml
- filename: lightup-catalogs-api-openapi.yml
  format: yaml
  label: Lightup Catalogs API
  slug: lightup-catalogs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-catalogs-api-openapi.yml
- filename: lightup-dashboard-chart-api-openapi.yml
  format: yaml
  label: Lightup Dashboard chart API
  slug: lightup-dashboard-chart-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-dashboard-chart-api-openapi.yml
- filename: lightup-datapoints-api-openapi.yml
  format: yaml
  label: Lightup Datapoints API
  slug: lightup-datapoints-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-datapoints-api-openapi.yml
- filename: lightup-health-check-api-openapi.yml
  format: yaml
  label: Lightup Health check API
  slug: lightup-health-check-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-health-check-api-openapi.yml
- filename: lightup-incidents-api-openapi.yml
  format: yaml
  label: Lightup Incidents API
  slug: lightup-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-incidents-api-openapi.yml
- filename: lightup-integrations-api-openapi.yml
  format: yaml
  label: Lightup Integrations API
  slug: lightup-integrations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-integrations-api-openapi.yml
- filename: lightup-metrics-api-openapi.yml
  format: yaml
  label: Lightup Metrics API
  slug: lightup-metrics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-metrics-api-openapi.yml
- filename: lightup-monitors-api-openapi.yml
  format: yaml
  label: Lightup Monitors API
  slug: lightup-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-monitors-api-openapi.yml
- filename: lightup-users-api-openapi.yml
  format: yaml
  label: Lightup Users API
  slug: lightup-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-users-api-openapi.yml
- filename: lightup-workspaces-api-openapi.yml
  format: yaml
  label: Lightup Workspaces API
  slug: lightup-workspaces-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-workspaces-api-openapi.yml
- filename: lightup-data-sources-api-openapi.yml
  format: yaml
  label: Lightup Data Sources API
  slug: lightup-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/lightup/openapi/lightup-data-sources-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export-controlled and excluded data
    text: to process, send, or store Excluded Data
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
name: Lightup
provenance_date: '2026-11-09'
provider_name: Lightup
provider_slug: lightup
slug: lightup-eligibility
source_date: '2026-11-09'
source_filename: lightup-eligibility.yml
source_heading: Eligibility
source_page: https://www.lightup.ai/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Lightup\naid: lightup\nurl: https://www.lightup.ai/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Export-controlled and excluded data\n  text: to process, send, or store Excluded Data\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/lightup/eligibility/lightup-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Lightup's own page on 2026-11-09.
synthetic: false
tags:
- Data Quality
- Data Observability
- Data Monitoring
- Anomaly Detection
- Data Engineering
- Analytics
- Incident Management
- Artificial Intelligence
- Data Governance
- Company
---
