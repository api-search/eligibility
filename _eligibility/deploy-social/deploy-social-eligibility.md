---
api_specs:
- filename: deploy-social-account-api-openapi.yml
  format: yaml
  label: deploy.social Account API
  slug: deploy-social-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deploy-social/openapi/deploy-social-account-api-openapi.yml
- filename: deploy-social-destinations-api-openapi.yml
  format: yaml
  label: deploy.social Destinations API
  slug: deploy-social-destinations-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deploy-social/openapi/deploy-social-destinations-api-openapi.yml
- filename: deploy-social-media-api-openapi.yml
  format: yaml
  label: deploy.social Media API
  slug: deploy-social-media-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deploy-social/openapi/deploy-social-media-api-openapi.yml
- filename: deploy-social-posts-api-openapi.yml
  format: yaml
  label: deploy.social Posts API
  slug: deploy-social-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/deploy-social/openapi/deploy-social-posts-api-openapi.yml
claim_count: 1
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You need to be at least 13 (and old enough to hold accounts on the platforms you connect).
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
name: deploy.social
provenance_date: '2026-11-09'
provider_name: deploy.social
provider_slug: deploy-social
slug: deploy-social-eligibility
source_date: '2026-11-09'
source_filename: deploy-social-eligibility.yml
source_heading: Eligibility
source_page: https://deploy.social/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: deploy.social\naid: deploy-social\nurl: https://deploy.social/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses: []\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '13'\n  text: You need to be at least 13 (and old enough to hold accounts on the platforms you connect).\n"
source_yaml_url: https://artifacts.apis.io/deploy-social/eligibility/deploy-social-eligibility.yml
stated_fields:
- minimum_age
summary_line: 1 quoted statement, read from deploy.social's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Social Media
- Video
- Short-Form Video
- Cross-Posting
- Scheduling
- Content Publishing
- MCP
---
