---
api_specs:
- filename: dailyhunt-catalog-api-openapi.yml
  format: yaml
  label: Dailyhunt Catalog API
  slug: dailyhunt-catalog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailyhunt/openapi/dailyhunt-catalog-api-openapi.yml
- filename: dailyhunt-channels-api-openapi.yml
  format: yaml
  label: Dailyhunt Channels API
  slug: dailyhunt-channels-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailyhunt/openapi/dailyhunt-channels-api-openapi.yml
- filename: dailyhunt-content-fetch-api-openapi.yml
  format: yaml
  label: Dailyhunt Content Fetch API
  slug: dailyhunt-content-fetch-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailyhunt/openapi/dailyhunt-content-fetch-api-openapi.yml
- filename: dailyhunt-cricket-api-openapi.yml
  format: yaml
  label: Dailyhunt Cricket API
  slug: dailyhunt-cricket-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailyhunt/openapi/dailyhunt-cricket-api-openapi.yml
- filename: dailyhunt-feedback-api-openapi.yml
  format: yaml
  label: Dailyhunt Feedback API
  slug: dailyhunt-feedback-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailyhunt/openapi/dailyhunt-feedback-api-openapi.yml
- filename: dailyhunt-languages-api-openapi.yml
  format: yaml
  label: Dailyhunt Languages API
  slug: dailyhunt-languages-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailyhunt/openapi/dailyhunt-languages-api-openapi.yml
- filename: dailyhunt-products-api-openapi.yml
  format: yaml
  label: Dailyhunt Products API
  slug: dailyhunt-products-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailyhunt/openapi/dailyhunt-products-api-openapi.yml
- filename: dailyhunt-tracking-api-openapi.yml
  format: yaml
  label: Dailyhunt Tracking API
  slug: dailyhunt-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/dailyhunt/openapi/dailyhunt-tracking-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Use and access to the Platform is available to all persons, directly or through legally authorized agents, who can be legally bound by contract
    type: individual
  minimum_age:
    text: If You are a minor i.e. under the age of 18 years, You shall not register as a User of the Platform and shall not access or use the Platform.
    value: '18'
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
name: Dailyhunt
provenance_date: '2026-11-09'
provider_name: Dailyhunt
provider_slug: dailyhunt
slug: dailyhunt-eligibility
source_date: '2026-11-09'
source_filename: dailyhunt-eligibility.yml
source_heading: Eligibility
source_page: https://direct.dailyhunt.in/help/v2/ad-terms-and-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Dailyhunt\naid: dailyhunt\nurl: https://direct.dailyhunt.in/help/v2/ad-terms-and-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: Use and access to the Platform is available to all persons, directly or through legally authorized agents,\n    who can be legally bound by contract\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: If You are a minor i.e. under the age of 18 years, You shall not register as a User of the Platform and\n \
  \   shall not access or use the Platform.\n"
source_yaml_url: https://artifacts.apis.io/dailyhunt/eligibility/dailyhunt-eligibility.yml
stated_fields:
- entity_types
- minimum_age
summary_line: 2 quoted statements, read from Dailyhunt's own page on 2026-11-09.
synthetic: false
tags:
- Company
- News
- Media
- Content Syndication
- Content
- Advertising
- Video
- Localization
- India
- Mobile
---
