---
api_specs:
- filename: soda-data-attributes-api-openapi.yml
  format: yaml
  label: Soda Attributes API
  slug: soda-data-attributes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-attributes-api-openapi.yml
- filename: soda-data-checks-api-openapi.yml
  format: yaml
  label: Soda Checks API
  slug: soda-data-checks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-checks-api-openapi.yml
- filename: soda-data-contracts-api-openapi.yml
  format: yaml
  label: Soda Contracts API
  slug: soda-data-contracts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-contracts-api-openapi.yml
- filename: soda-data-data-standards-api-openapi.yml
  format: yaml
  label: Soda Data Standards API
  slug: soda-data-data-standards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-data-standards-api-openapi.yml
- filename: soda-data-datasets-api-openapi.yml
  format: yaml
  label: Soda Datasets API
  slug: soda-data-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-datasets-api-openapi.yml
- filename: soda-data-discovered-datasets-api-openapi.yml
  format: yaml
  label: Soda Discovered Datasets API
  slug: soda-data-discovered-datasets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-discovered-datasets-api-openapi.yml
- filename: soda-data-incidents-api-openapi.yml
  format: yaml
  label: Soda Incidents API
  slug: soda-data-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-incidents-api-openapi.yml
- filename: soda-data-licensing-api-openapi.yml
  format: yaml
  label: Soda Licensing API
  slug: soda-data-licensing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-licensing-api-openapi.yml
- filename: soda-data-notification-rules-api-openapi.yml
  format: yaml
  label: Soda Notification Rules API
  slug: soda-data-notification-rules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-notification-rules-api-openapi.yml
- filename: soda-data-runners-api-openapi.yml
  format: yaml
  label: Soda Runners API
  slug: soda-data-runners-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-runners-api-openapi.yml
- filename: soda-data-scans-api-openapi.yml
  format: yaml
  label: Soda Scans API
  slug: soda-data-scans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-scans-api-openapi.yml
- filename: soda-data-secrets-api-openapi.yml
  format: yaml
  label: Soda Secrets API
  slug: soda-data-secrets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-secrets-api-openapi.yml
- filename: soda-data-users-api-openapi.yml
  format: yaml
  label: Soda Users API
  slug: soda-data-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-users-api-openapi.yml
- filename: soda-data-utility-api-openapi.yml
  format: yaml
  label: Soda Utility API
  slug: soda-data-utility-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-utility-api-openapi.yml
- filename: soda-data-data-sources-api-openapi.yml
  format: yaml
  label: Soda Data Sources API
  slug: soda-data-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/soda-data/openapi/soda-data-data-sources-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: for customers residing within the United States of America or within Canada, Soda Data Inc., a Delaware Corporation
  entity_types:
  - text: The Service is reserved to business Customers. Consumers cannot be a Customer.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: No automated decisions with legal effects
    text: Customer may not use AI Features for automated decision-making processes with legal effects.
  - summary: No personal or sensitive data in AI prompts
    text: Customer agrees that he will not include any personal or sensitive data in any Prompts to AI Features.
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
name: Soda
provenance_date: '2026-11-10'
provider_name: Soda
provider_slug: soda-data
slug: soda-data-eligibility
source_date: '2026-11-10'
source_filename: soda-data-eligibility.yml
source_heading: Eligibility
source_page: https://soda.io/legal/terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Soda\naid: soda-data\nurl: https://soda.io/legal/terms-and-conditions\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: for customers residing within the United States of America or within Canada, Soda Data Inc., a Delaware\n    Corporation\nentity_types:\n- type: business\n  text: The Service is reserved to business Customers. Consumers cannot be a Customer.\nrestricted_uses:\n- summary: No automated decisions with legal effects\n  text: Customer may not use AI Features for automated decision-making processes with legal effects.\n- summary: No personal or sensitive data in AI prompts\n\
  \  text: Customer agrees that he will not include any personal or sensitive data in any Prompts to AI Features.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/soda-data/eligibility/soda-data-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from Soda's own page on 2026-11-10.
synthetic: false
tags:
- AIOps
- Data Quality
- Data Observability
- Data Contracts
- Data Governance
- Anomaly Detection
- Data Monitoring
- Data Testing
---
