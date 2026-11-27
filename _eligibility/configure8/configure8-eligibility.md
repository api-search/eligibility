---
api_specs:
- filename: configure8-catalog-entities-api-openapi.yml
  format: yaml
  label: Configure8 Catalog Entities API
  slug: configure8-catalog-entities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-catalog-entities-api-openapi.yml
- filename: configure8-catalog-relations-api-openapi.yml
  format: yaml
  label: Configure8 Catalog Relations API
  slug: configure8-catalog-relations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-catalog-relations-api-openapi.yml
- filename: configure8-deployments-api-openapi.yml
  format: yaml
  label: Configure8 Deployments API
  slug: configure8-deployments-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-deployments-api-openapi.yml
- filename: configure8-scorecards-api-openapi.yml
  format: yaml
  label: Configure8 Scorecards API
  slug: configure8-scorecards-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-scorecards-api-openapi.yml
- filename: configure8-users-api-openapi.yml
  format: yaml
  label: Configure8 Users API
  slug: configure8-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-users-api-openapi.yml
- filename: configure8-catalog-entity-api-openapi.yml
  format: yaml
  label: Configure8 Catalog Entity API
  slug: configure8-catalog-entity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-catalog-entity-api-openapi.yml
- filename: configure8-catalog-entity-batch-api-openapi.yml
  format: yaml
  label: Configure8 Catalog Entity Batch API
  slug: configure8-catalog-entity-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-catalog-entity-batch-api-openapi.yml
- filename: configure8-catalog-entity-metadata-api-openapi.yml
  format: yaml
  label: Configure8 Catalog Entity Metadata API
  slug: configure8-catalog-entity-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-catalog-entity-metadata-api-openapi.yml
- filename: configure8-catalog-relation-api-openapi.yml
  format: yaml
  label: Configure8 Catalog Relation API
  slug: configure8-catalog-relation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-catalog-relation-api-openapi.yml
- filename: configure8-credential-api-openapi.yml
  format: yaml
  label: Configure8 Credential API
  slug: configure8-credential-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-credential-api-openapi.yml
- filename: configure8-deployment-api-openapi.yml
  format: yaml
  label: Configure8 Deployment API
  slug: configure8-deployment-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-deployment-api-openapi.yml
- filename: configure8-module-settings-api-openapi.yml
  format: yaml
  label: Configure8 Module Settings API
  slug: configure8-module-settings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-module-settings-api-openapi.yml
- filename: configure8-private-scim-api-openapi.yml
  format: yaml
  label: Configure8 Private SCIM API
  slug: configure8-private-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-private-scim-api-openapi.yml
- filename: configure8-scim-api-openapi.yml
  format: yaml
  label: Configure8 SCIM API
  slug: configure8-scim-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-scim-api-openapi.yml
- filename: configure8-scorecard-api-openapi.yml
  format: yaml
  label: Configure8 Scorecard API
  slug: configure8-scorecard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-scorecard-api-openapi.yml
- filename: configure8-sync-api-openapi.yml
  format: yaml
  label: Configure8 Sync API
  slug: configure8-sync-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-sync-api-openapi.yml
- filename: configure8-templates-api-openapi.yml
  format: yaml
  label: Configure8 Templates API
  slug: configure8-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/configure8/openapi/configure8-templates-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: All Authorized Users must be 18 years of age or older to visit or use any of the Services in any manner.
    value: '18'
  restricted_uses:
  - summary: High-risk activities excluded
    text: The Services are not designed or intended for use or resale in high-risk or hazardous environments requiring fail -safe performance
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
name: Configure8
provenance_date: '2026-11-09'
provider_name: Configure8
provider_slug: configure8
slug: configure8-eligibility
source_date: '2026-11-09'
source_filename: configure8-eligibility.yml
source_heading: Eligibility
source_page: https://configure8.io/tos.pdf
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Configure8\naid: configure8\nurl: https://configure8.io/tos.pdf\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\n  truncated: true\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: High-risk activities excluded\n  text: The Services are not designed or intended for use or resale in high-risk or hazardous environments requiring\n    fail -safe performance\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: All Authorized Users must be 18 years of age or older to visit or use any of the Services in any manner.\n"
source_yaml_url: https://artifacts.apis.io/configure8/eligibility/configure8-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Configure8's own page on 2026-11-09.
synthetic: false
tags:
- Catalog
- Cloud Cost
- Developer Experience
- DevOps
- Internal Developer Portal
- Platform Engineering
- Scorecards
- Self-Service
- Service Catalog
- SRE
- Developer Portal
---
