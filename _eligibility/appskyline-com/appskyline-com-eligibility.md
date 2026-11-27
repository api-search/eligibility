---
api_specs:
- filename: appskyline-com-apps-api-openapi.yml
  format: yaml
  label: AppSkyline Apps API
  slug: appskyline-com-apps-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appskyline-com/openapi/appskyline-com-apps-api-openapi.yml
- filename: appskyline-com-batch-api-openapi.yml
  format: yaml
  label: AppSkyline Batch API
  slug: appskyline-com-batch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appskyline-com/openapi/appskyline-com-batch-api-openapi.yml
- filename: appskyline-com-google-play-publishing-api-openapi.yml
  format: yaml
  label: AppSkyline Google Play Publishing API
  slug: appskyline-com-google-play-publishing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appskyline-com/openapi/appskyline-com-google-play-publishing-api-openapi.yml
- filename: appskyline-com-keywords-api-openapi.yml
  format: yaml
  label: AppSkyline Keywords API
  slug: appskyline-com-keywords-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appskyline-com/openapi/appskyline-com-keywords-api-openapi.yml
- filename: appskyline-com-metadata-api-openapi.yml
  format: yaml
  label: AppSkyline Metadata API
  slug: appskyline-com-metadata-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appskyline-com/openapi/appskyline-com-metadata-api-openapi.yml
- filename: appskyline-com-review-status-api-openapi.yml
  format: yaml
  label: AppSkyline Review Status API
  slug: appskyline-com-review-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appskyline-com/openapi/appskyline-com-review-status-api-openapi.yml
- filename: appskyline-com-sandbox-api-openapi.yml
  format: yaml
  label: AppSkyline Sandbox API
  slug: appskyline-com-sandbox-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appskyline-com/openapi/appskyline-com-sandbox-api-openapi.yml
- filename: appskyline-com-stats-api-openapi.yml
  format: yaml
  label: AppSkyline Stats API
  slug: appskyline-com-stats-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appskyline-com/openapi/appskyline-com-stats-api-openapi.yml
- filename: appskyline-com-webhook-subscriptions-api-openapi.yml
  format: yaml
  label: AppSkyline Webhook subscriptions API
  slug: appskyline-com-webhook-subscriptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/appskyline-com/openapi/appskyline-com-webhook-subscriptions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act for a business or another organization, you must have authority to bind it.
    type: business
  - text: a consumer uses it mainly for personal purposes.
    type: individual
  minimum_age:
    text: You must be legally able to enter into this agreement.
    value: null
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
name: AppSkyline
provenance_date: '2026-11-09'
provider_name: AppSkyline
provider_slug: appskyline-com
slug: appskyline-com-eligibility
source_date: '2026-11-09'
source_filename: appskyline-com-eligibility.yml
source_heading: Eligibility
source_page: https://www.appskyline.com/en/terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AppSkyline\naid: appskyline-com\nurl: https://www.appskyline.com/en/terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act for a business or another organization, you must have authority to bind it.\n- type: individual\n  text: a consumer uses it mainly for personal purposes.\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: You must be legally able to enter into this agreement.\n"
source_yaml_url: https://artifacts.apis.io/appskyline-com/eligibility/appskyline-com-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 3 quoted statements, read from AppSkyline's own page on 2026-11-09.
synthetic: false
tags:
- App Store Optimization
- Analytics
- Marketing
- Software-as-a-Service
- Developer Tools
- Company
---
