---
api_specs:
- filename: sifflet-assets-api-openapi.yml
  format: yaml
  label: Sifflet Assets API
  slug: sifflet-assets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-assets-api-openapi.yml
- filename: sifflet-calendars-api-openapi.yml
  format: yaml
  label: Sifflet Calendars API
  slug: sifflet-calendars-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-calendars-api-openapi.yml
- filename: sifflet-credentials-api-openapi.yml
  format: yaml
  label: Sifflet Credentials API
  slug: sifflet-credentials-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-credentials-api-openapi.yml
- filename: sifflet-dbt-integration-api-openapi.yml
  format: yaml
  label: Sifflet dbt integration API
  slug: sifflet-dbt-integration-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-dbt-integration-api-openapi.yml
- filename: sifflet-declarative-assets-and-lineage-api-openapi.yml
  format: yaml
  label: Sifflet Declarative Assets and Lineage API
  slug: sifflet-declarative-assets-and-lineage-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-declarative-assets-and-lineage-api-openapi.yml
- filename: sifflet-domains-api-openapi.yml
  format: yaml
  label: Sifflet Domains API
  slug: sifflet-domains-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-domains-api-openapi.yml
- filename: sifflet-external-catalog-api-openapi.yml
  format: yaml
  label: Sifflet External Catalog API
  slug: sifflet-external-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-external-catalog-api-openapi.yml
- filename: sifflet-notification-rules-api-openapi.yml
  format: yaml
  label: Sifflet Notification Rules API
  slug: sifflet-notification-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-notification-rules-api-openapi.yml
- filename: sifflet-rule-api-openapi.yml
  format: yaml
  label: Sifflet Rule API
  slug: sifflet-rule-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-rule-api-openapi.yml
- filename: sifflet-rule-run-api-openapi.yml
  format: yaml
  label: Sifflet Rule Run API
  slug: sifflet-rule-run-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-rule-run-api-openapi.yml
- filename: sifflet-sources-deprecated-api-openapi.yml
  format: yaml
  label: Sifflet Sources (deprecated) API
  slug: sifflet-sources-deprecated-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-sources-deprecated-api-openapi.yml
- filename: sifflet-sources-v2-api-openapi.yml
  format: yaml
  label: Sifflet Sources (v2) API
  slug: sifflet-sources-v2-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-sources-v2-api-openapi.yml
- filename: sifflet-teams-api-openapi.yml
  format: yaml
  label: Sifflet Teams API
  slug: sifflet-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-teams-api-openapi.yml
- filename: sifflet-users-api-openapi.yml
  format: yaml
  label: Sifflet Users API
  slug: sifflet-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-users-api-openapi.yml
- filename: sifflet-workspace-api-openapi.yml
  format: yaml
  label: Sifflet Workspace API
  slug: sifflet-workspace-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/sifflet/openapi/sifflet-workspace-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: '“User”: This term refers to any person who uses the site or any of the services offered by the site.'
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Commercial use of contents
    text: The use of the contents for commercial purposes is strictly prohibited.
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
name: Sifflet
provenance_date: '2026-11-10'
provider_name: Sifflet
provider_slug: sifflet
slug: sifflet-eligibility
source_date: '2026-11-10'
source_filename: sifflet-eligibility.yml
source_heading: Eligibility
source_page: https://www.siffletdata.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Sifflet\naid: sifflet\nurl: https://www.siffletdata.com/terms-of-use\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: '“User”: This term refers to any person who uses the site or any of the services offered by the site.'\nrestricted_uses:\n- summary: Commercial use of contents\n  text: The use of the contents for commercial purposes is strictly prohibited.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/sifflet/eligibility/sifflet-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from Sifflet's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Data Analytics
- Data Observability
- Data Quality
- Data Catalog
- Data Lineage
- Data Governance
- Monitoring
- Metadata
- AI Agents
---
