---
api_specs:
- filename: immuta-access-request-api-openapi.yml
  format: yaml
  label: Immuta Access Request API
  slug: immuta-access-request-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-access-request-api-openapi.yml
- filename: immuta-asset-api-openapi.yml
  format: yaml
  label: Immuta Asset API
  slug: immuta-asset-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-asset-api-openapi.yml
- filename: immuta-auth-api-openapi.yml
  format: yaml
  label: Immuta Auth API
  slug: immuta-auth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-auth-api-openapi.yml
- filename: immuta-data-product-api-openapi.yml
  format: yaml
  label: Immuta Data Product API
  slug: immuta-data-product-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-data-product-api-openapi.yml
- filename: immuta-data-source-api-openapi.yml
  format: yaml
  label: Immuta Data Source API
  slug: immuta-data-source-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-data-source-api-openapi.yml
- filename: immuta-data-use-agreement-api-openapi.yml
  format: yaml
  label: Immuta Data Use Agreement API
  slug: immuta-data-use-agreement-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-data-use-agreement-api-openapi.yml
- filename: immuta-health-api-openapi.yml
  format: yaml
  label: Immuta Health API
  slug: immuta-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-health-api-openapi.yml
- filename: immuta-metadata-api-openapi.yml
  format: yaml
  label: Immuta Metadata API
  slug: immuta-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-metadata-api-openapi.yml
- filename: immuta-notification-api-openapi.yml
  format: yaml
  label: Immuta Notification API
  slug: immuta-notification-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-notification-api-openapi.yml
- filename: immuta-request-form-api-openapi.yml
  format: yaml
  label: Immuta Request Form API
  slug: immuta-request-form-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-request-form-api-openapi.yml
- filename: immuta-settings-api-openapi.yml
  format: yaml
  label: Immuta Settings API
  slug: immuta-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/immuta/openapi/immuta-settings-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are using the Services on behalf of any entity, you represent and warrant that you are authorized to accept these Terms on such entity’s behalf
    type: business
  minimum_age:
    text: In order to create an account, you must be 13 years of age or older.
    value: '13'
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
name: Immuta
provenance_date: '2026-11-09'
provider_name: Immuta
provider_slug: immuta
slug: immuta-eligibility
source_date: '2026-11-09'
source_filename: immuta-eligibility.yml
source_heading: Eligibility
source_page: https://www.immuta.com/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Immuta\naid: immuta\nurl: https://www.immuta.com/terms-of-service\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are using the Services on behalf of any entity, you represent and warrant that you are authorized\n    to accept these Terms on such entity’s behalf\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: In order to create an account, you must be 13 years of age or older.\n"
source_yaml_url: https://artifacts.apis.io/immuta/eligibility/immuta-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Immuta's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Data Governance
- Data Access Control
- Data Security
- Privacy
- Policy Management
- Data Marketplace
- Compliance
- Snowflake
- Databricks
- Analytics
- Agentic Data Access
---
