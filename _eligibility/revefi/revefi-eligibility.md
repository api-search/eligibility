---
api_specs:
- filename: revefi-create-a-custom-data-quality-monitor-api-openapi.yml
  format: yaml
  label: Revefi Create a Custom Data Quality Monitor API
  slug: revefi-create-a-custom-data-quality-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revefi/openapi/revefi-create-a-custom-data-quality-monitor-api-openapi.yml
- filename: revefi-delete-an-existing-custom-data-quality-monitor-api-openapi.yml
  format: yaml
  label: Revefi Delete an existing Custom Data Quality Monitor API
  slug: revefi-delete-an-existing-custom-data-quality-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revefi/openapi/revefi-delete-an-existing-custom-data-quality-monitor-api-openapi.yml
- filename: revefi-get-custom-data-quality-monitors-api-openapi.yml
  format: yaml
  label: Revefi Get Custom Data Quality Monitors API
  slug: revefi-get-custom-data-quality-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revefi/openapi/revefi-get-custom-data-quality-monitors-api-openapi.yml
- filename: revefi-get-custom-data-quality-monitors-by-artifact-api-openapi.yml
  format: yaml
  label: Revefi Get Custom Data Quality Monitors by Artifact API
  slug: revefi-get-custom-data-quality-monitors-by-artifact-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revefi/openapi/revefi-get-custom-data-quality-monitors-by-artifact-api-openapi.yml
- filename: revefi-run-monitors-api-openapi.yml
  format: yaml
  label: Revefi Run Monitors API
  slug: revefi-run-monitors-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revefi/openapi/revefi-run-monitors-api-openapi.yml
- filename: revefi-update-an-existing-custom-data-quality-monitor-api-openapi.yml
  format: yaml
  label: Revefi Update an existing Custom Data Quality Monitor API
  slug: revefi-update-an-existing-custom-data-quality-monitor-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/revefi/openapi/revefi-update-an-existing-custom-data-quality-monitor-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you open a Revefi account on behalf of a company, organization, or other entity, then (a) ”you” includes you and that entity
    type: business
  minimum_age:
    text: You must be 18 years old or older to use or access the Services.
    value: '18'
  restricted_uses:
  - summary: Unlawful or prohibited activity
    text: using the Services in any manner that violates any applicable law, regulation or legal requirement or obligation
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
name: Revefi
provenance_date: '2026-11-10'
provider_name: Revefi
provider_slug: revefi
slug: revefi-eligibility
source_date: '2026-11-10'
source_filename: revefi-eligibility.yml
source_heading: Eligibility
source_page: https://www.revefi.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Revefi\naid: revefi\nurl: https://www.revefi.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you open a Revefi account on behalf of a company, organization, or other entity, then (a) ”you” includes\n    you and that entity\nrestricted_uses:\n- summary: Unlawful or prohibited activity\n  text: using the Services in any manner that violates any applicable law, regulation or legal requirement or obligation\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You\
  \ must be 18 years old or older to use or access the Services.\n"
source_yaml_url: https://artifacts.apis.io/revefi/eligibility/revefi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Revefi's own page on 2026-11-10.
synthetic: false
tags:
- Data
- Data Quality
- Data Observability
- FinOps
- Cost Optimization
- Analytics
- Snowflake
- Databricks
- BigQuery
- Artificial Intelligence
- MCP
---
