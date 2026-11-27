---
api_specs:
- filename: anomalo-access-groups-api-openapi.yml
  format: yaml
  label: Anomalo Access Groups API
  slug: anomalo-access-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-access-groups-api-openapi.yml
- filename: anomalo-api-keys-api-openapi.yml
  format: yaml
  label: Anomalo API Keys API
  slug: anomalo-api-keys-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-api-keys-api-openapi.yml
- filename: anomalo-check-runs-api-openapi.yml
  format: yaml
  label: Anomalo Check Runs API
  slug: anomalo-check-runs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-check-runs-api-openapi.yml
- filename: anomalo-checks-api-openapi.yml
  format: yaml
  label: Anomalo Checks API
  slug: anomalo-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-checks-api-openapi.yml
- filename: anomalo-document-collections-api-openapi.yml
  format: yaml
  label: Anomalo Document Collections API
  slug: anomalo-document-collections-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-document-collections-api-openapi.yml
- filename: anomalo-documents-api-openapi.yml
  format: yaml
  label: Anomalo Documents API
  slug: anomalo-documents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-documents-api-openapi.yml
- filename: anomalo-exports-api-openapi.yml
  format: yaml
  label: Anomalo Exports API
  slug: anomalo-exports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-exports-api-openapi.yml
- filename: anomalo-issues-api-openapi.yml
  format: yaml
  label: Anomalo Issues API
  slug: anomalo-issues-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-issues-api-openapi.yml
- filename: anomalo-labels-api-openapi.yml
  format: yaml
  label: Anomalo Labels API
  slug: anomalo-labels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-labels-api-openapi.yml
- filename: anomalo-lineage-api-openapi.yml
  format: yaml
  label: Anomalo Lineage API
  slug: anomalo-lineage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-lineage-api-openapi.yml
- filename: anomalo-notification-channels-api-openapi.yml
  format: yaml
  label: Anomalo Notification Channels API
  slug: anomalo-notification-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-notification-channels-api-openapi.yml
- filename: anomalo-organizations-api-openapi.yml
  format: yaml
  label: Anomalo Organizations API
  slug: anomalo-organizations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-organizations-api-openapi.yml
- filename: anomalo-sensitive-columns-api-openapi.yml
  format: yaml
  label: Anomalo Sensitive Columns API
  slug: anomalo-sensitive-columns-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-sensitive-columns-api-openapi.yml
- filename: anomalo-system-api-openapi.yml
  format: yaml
  label: Anomalo System API
  slug: anomalo-system-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-system-api-openapi.yml
- filename: anomalo-tables-api-openapi.yml
  format: yaml
  label: Anomalo Tables API
  slug: anomalo-tables-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-tables-api-openapi.yml
- filename: anomalo-tasks-api-openapi.yml
  format: yaml
  label: Anomalo Tasks API
  slug: anomalo-tasks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-tasks-api-openapi.yml
- filename: anomalo-users-api-openapi.yml
  format: yaml
  label: Anomalo Users API
  slug: anomalo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-users-api-openapi.yml
- filename: anomalo-warehouses-api-openapi.yml
  format: yaml
  label: Anomalo Warehouses API
  slug: anomalo-warehouses-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/anomalo/openapi/anomalo-warehouses-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: allows you or the organization you represent (“the Customer “) to use Services
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Export control restrictions
    text: Customer shall not, directly or indirectly, export, re-export, or release the Services or the underlying software or technology
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
name: Anomalo
provenance_date: '2026-11-09'
provider_name: Anomalo
provider_slug: anomalo
slug: anomalo-eligibility
source_date: '2026-11-09'
source_filename: anomalo-eligibility.yml
source_heading: Eligibility
source_page: https://www.anomalo.com/legal/subscription/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Anomalo\naid: anomalo\nurl: https://www.anomalo.com/legal/subscription/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: allows you or the organization you represent (“the Customer “) to use Services\nrestricted_uses:\n- summary: Export control restrictions\n  text: Customer shall not, directly or indirectly, export, re-export, or release the Services or the underlying\n    software or technology\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/anomalo/eligibility/anomalo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Anomalo's own page on 2026-11-09.
synthetic: false
tags:
- Data Quality
- Data Observability
- Data Monitoring
- Anomaly Detection
- Data Governance
- Data Lineage
- Data Profiling
- Data Validation
- Data Engineering
- Machine Learning
- Snowflake
- Databricks
- BigQuery
- Enterprise Data
- MCP
- Agent-Native
---
