---
api_specs:
- filename: seismic-content-analytics-api-openapi.yml
  format: yaml
  label: Seismic Content Analytics API
  slug: seismic-content-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-content-analytics-api-openapi.yml
- filename: seismic-content-api-openapi.yml
  format: yaml
  label: Seismic Content API
  slug: seismic-content-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-content-api-openapi.yml
- filename: seismic-content-profiles-api-openapi.yml
  format: yaml
  label: Seismic Content Profiles API
  slug: seismic-content-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-content-profiles-api-openapi.yml
- filename: seismic-content-properties-api-openapi.yml
  format: yaml
  label: Seismic Content Properties API
  slug: seismic-content-properties-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-content-properties-api-openapi.yml
- filename: seismic-data-sources-api-openapi.yml
  format: yaml
  label: Seismic Data Sources API
  slug: seismic-data-sources-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-data-sources-api-openapi.yml
- filename: seismic-delivery-analytics-api-openapi.yml
  format: yaml
  label: Seismic Delivery Analytics API
  slug: seismic-delivery-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-delivery-analytics-api-openapi.yml
- filename: seismic-delivery-api-openapi.yml
  format: yaml
  label: Seismic Delivery API
  slug: seismic-delivery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-delivery-api-openapi.yml
- filename: seismic-folders-api-openapi.yml
  format: yaml
  label: Seismic Folders API
  slug: seismic-folders-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-folders-api-openapi.yml
- filename: seismic-generation-jobs-api-openapi.yml
  format: yaml
  label: Seismic Generation Jobs API
  slug: seismic-generation-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-generation-jobs-api-openapi.yml
- filename: seismic-groups-api-openapi.yml
  format: yaml
  label: Seismic Groups API
  slug: seismic-groups-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-groups-api-openapi.yml
- filename: seismic-livedocs-api-openapi.yml
  format: yaml
  label: Seismic LiveDocs API
  slug: seismic-livedocs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-livedocs-api-openapi.yml
- filename: seismic-reports-api-openapi.yml
  format: yaml
  label: Seismic Reports API
  slug: seismic-reports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-reports-api-openapi.yml
- filename: seismic-roles-api-openapi.yml
  format: yaml
  label: Seismic Roles API
  slug: seismic-roles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-roles-api-openapi.yml
- filename: seismic-teams-api-openapi.yml
  format: yaml
  label: Seismic Teams API
  slug: seismic-teams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-teams-api-openapi.yml
- filename: seismic-templates-api-openapi.yml
  format: yaml
  label: Seismic Templates API
  slug: seismic-templates-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-templates-api-openapi.yml
- filename: seismic-user-analytics-api-openapi.yml
  format: yaml
  label: Seismic User Analytics API
  slug: seismic-user-analytics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-user-analytics-api-openapi.yml
- filename: seismic-users-api-openapi.yml
  format: yaml
  label: Seismic Users API
  slug: seismic-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/seismic/openapi/seismic-users-api-openapi.yml
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
  - summary: Sensitive personal data
    text: (f) use the Subscription Services to store, transmit or display financial data of individuals, health data of individuals, or other sensitive data as described in Article 9, Paragraph 1 of the General Data Privacy Regulation (GDPR) or otherwise defined under applicable law.
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
name: Seismic
provenance_date: '2026-11-10'
provider_name: Seismic
provider_slug: seismic
slug: seismic-eligibility
source_date: '2026-11-10'
source_filename: seismic-eligibility.yml
source_heading: Eligibility
source_page: https://www.seismic.com/legal/terms-agreements/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Seismic\naid: seismic\nurl: https://www.seismic.com/legal/terms-agreements/terms-of-service/\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Sensitive personal data\n  text: (f) use the Subscription Services to store, transmit or display financial data of individuals, health data\n    of individuals, or other sensitive data as described in Article 9, Paragraph 1 of the General Data Privacy Regulation\n    (GDPR) or otherwise defined under applicable law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/seismic/eligibility/seismic-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Seismic's own page on 2026-11-10.
synthetic: false
tags:
- Sales Enablement
- Content Management
- Document Generation
- Sales Content
- Buyer Engagement
- Revenue Enablement
- Analytics
- Learning
- SCIM
- MCP
---
