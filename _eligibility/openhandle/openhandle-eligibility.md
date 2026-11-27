---
api_specs:
- filename: openhandle-instagram-api-openapi.yml
  format: yaml
  label: Openhandle Instagram API
  slug: openhandle-instagram-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-instagram-api-openapi.yml
- filename: openhandle-reddit-api-openapi.yml
  format: yaml
  label: Openhandle Reddit API
  slug: openhandle-reddit-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-reddit-api-openapi.yml
- filename: openhandle-test-data-api-openapi.yml
  format: yaml
  label: Openhandle Test Data API
  slug: openhandle-test-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-test-data-api-openapi.yml
- filename: openhandle-tiktok-api-openapi.yml
  format: yaml
  label: Openhandle Tiktok API
  slug: openhandle-tiktok-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-tiktok-api-openapi.yml
- filename: openhandle-twitter-api-openapi.yml
  format: yaml
  label: Openhandle Twitter API
  slug: openhandle-twitter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-twitter-api-openapi.yml
- filename: openhandle-utilities-api-openapi.yml
  format: yaml
  label: Openhandle Utilities API
  slug: openhandle-utilities-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/openhandle/openapi/openhandle-utilities-api-openapi.yml
claim_count: 2
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
  - summary: Harassment or surveillance of private persons
    text: harass, stalk, or surveil private persons, or build tools whose purpose is to target private persons;
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must verify your email address before you can make live requests.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Openhandle
provenance_date: '2026-11-10'
provider_name: Openhandle
provider_slug: openhandle
slug: openhandle-eligibility
source_date: '2026-11-10'
source_filename: openhandle-eligibility.yml
source_heading: Eligibility
source_page: https://openhandle.dev/legal/terms-of-service
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Openhandle\naid: openhandle\nurl: https://openhandle.dev/legal/terms-of-service\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Harassment or surveillance of private persons\n  text: harass, stalk, or surveil private persons, or build tools whose purpose is to target private persons;\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You must verify your email address before you can make live requests.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/openhandle/eligibility/openhandle-eligibility.yml
stated_fields:
- restricted_uses
- verification
summary_line: 2 quoted statements, read from Openhandle's own page on 2026-11-10.
synthetic: false
tags:
- Social Data
- Instagram
- TikTok
- Twitter
- Reddit
- Public Data
- social-media-api
- MCP
- creator-analytics
- Social Listening
---
