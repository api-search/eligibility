---
api_specs:
- filename: newsblur-authentication-api-openapi.yml
  format: yaml
  label: NewsBlur Authentication API
  slug: newsblur-authentication-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newsblur/openapi/newsblur-authentication-api-openapi.yml
- filename: newsblur-classifiers-api-openapi.yml
  format: yaml
  label: NewsBlur Classifiers API
  slug: newsblur-classifiers-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newsblur/openapi/newsblur-classifiers-api-openapi.yml
- filename: newsblur-feed-management-api-openapi.yml
  format: yaml
  label: NewsBlur Feed Management API
  slug: newsblur-feed-management-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newsblur/openapi/newsblur-feed-management-api-openapi.yml
- filename: newsblur-feeds-api-openapi.yml
  format: yaml
  label: NewsBlur Feeds API
  slug: newsblur-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newsblur/openapi/newsblur-feeds-api-openapi.yml
- filename: newsblur-import-export-api-openapi.yml
  format: yaml
  label: NewsBlur Import Export API
  slug: newsblur-import-export-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newsblur/openapi/newsblur-import-export-api-openapi.yml
- filename: newsblur-social-api-openapi.yml
  format: yaml
  label: NewsBlur Social API
  slug: newsblur-social-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newsblur/openapi/newsblur-social-api-openapi.yml
- filename: newsblur-stories-api-openapi.yml
  format: yaml
  label: NewsBlur Stories API
  slug: newsblur-stories-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/newsblur/openapi/newsblur-stories-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person, geographic region or jurisdiction.
  minimum_age:
    text: you represent that you are at least the age of majority in your state or province of residence
    value: age of majority
  restricted_uses:
  - summary: Prohibited uses list
    text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose'
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
name: NewsBlur
provenance_date: '2026-11-10'
provider_name: NewsBlur
provider_slug: newsblur
slug: newsblur-eligibility
source_date: '2026-11-10'
source_filename: newsblur-eligibility.yml
source_heading: Eligibility
source_page: https://www.newsblur.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: NewsBlur\naid: newsblur\nurl: https://www.newsblur.com/tos\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: We reserve the right, but are not obligated, to limit the sales of our products or Services to any person,\n    geographic region or jurisdiction.\nentity_types: []\nrestricted_uses:\n- summary: Prohibited uses list\n  text: 'you are prohibited from using the site or its content: (a) for any unlawful purpose'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: age of majority\n  text: you represent that you are at least the\
  \ age of majority in your state or province of residence\n"
source_yaml_url: https://artifacts.apis.io/newsblur/eligibility/newsblur-eligibility.yml
stated_fields:
- countries
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from NewsBlur's own page on 2026-11-10.
synthetic: false
tags:
- Company
- RSS
- News
- Feed Reader
- Aggregator
- Social
- Content
- Media
- Open Source
- MCP
---
