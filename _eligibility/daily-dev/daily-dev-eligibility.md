---
api_specs:
- filename: daily-dev-bookmarks-api-openapi.yml
  format: yaml
  label: daily-dev Bookmarks API
  slug: daily-dev-bookmarks-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-bookmarks-api-openapi.yml
- filename: daily-dev-custom-feeds-api-openapi.yml
  format: yaml
  label: daily-dev Custom Feeds API
  slug: daily-dev-custom-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-custom-feeds-api-openapi.yml
- filename: daily-dev-experiences-api-openapi.yml
  format: yaml
  label: daily-dev Experiences API
  slug: daily-dev-experiences-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-experiences-api-openapi.yml
- filename: daily-dev-feed-filters-api-openapi.yml
  format: yaml
  label: daily-dev Feed Filters API
  slug: daily-dev-feed-filters-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-feed-filters-api-openapi.yml
- filename: daily-dev-feeds-api-openapi.yml
  format: yaml
  label: daily-dev Feeds API
  slug: daily-dev-feeds-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-feeds-api-openapi.yml
- filename: daily-dev-for-you-api-openapi.yml
  format: yaml
  label: daily-dev For You API
  slug: daily-dev-for-you-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-for-you-api-openapi.yml
- filename: daily-dev-notifications-api-openapi.yml
  format: yaml
  label: daily-dev Notifications API
  slug: daily-dev-notifications-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-notifications-api-openapi.yml
- filename: daily-dev-plugins-api-openapi.yml
  format: yaml
  label: daily-dev Plugins API
  slug: daily-dev-plugins-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-plugins-api-openapi.yml
- filename: daily-dev-posts-api-openapi.yml
  format: yaml
  label: daily-dev Posts API
  slug: daily-dev-posts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-posts-api-openapi.yml
- filename: daily-dev-profile-api-openapi.yml
  format: yaml
  label: daily-dev Profile API
  slug: daily-dev-profile-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-profile-api-openapi.yml
- filename: daily-dev-recommend-api-openapi.yml
  format: yaml
  label: daily-dev Recommend API
  slug: daily-dev-recommend-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-recommend-api-openapi.yml
- filename: daily-dev-search-api-openapi.yml
  format: yaml
  label: daily-dev Search API
  slug: daily-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-search-api-openapi.yml
- filename: daily-dev-stack-api-openapi.yml
  format: yaml
  label: daily-dev Stack API
  slug: daily-dev-stack-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-stack-api-openapi.yml
- filename: daily-dev-tags-api-openapi.yml
  format: yaml
  label: daily-dev Tags API
  slug: daily-dev-tags-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/daily-dev/openapi/daily-dev-tags-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: this Agreement constitutes the legally binding agreement between you (either an individual or an entity) and the Company
    type: individual
  minimum_age:
    text: you are at least 18 years old
    value: '18'
  restricted_uses:
  - summary: No groups for illegal promotion
    text: You may not create any Group in order to promote illegal activities, products, or services
  - summary: No competing products via Public API
    text: use the Public API, or any data returned by the Public API, to develop, operate, support, or contribute to a Competing Product
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
name: daily-dev
provenance_date: '2026-11-09'
provider_name: daily-dev
provider_slug: daily-dev
slug: daily-dev-eligibility
source_date: '2026-11-09'
source_filename: daily-dev-eligibility.yml
source_heading: Eligibility
source_page: https://daily.dev/tos/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: daily-dev\naid: daily-dev\nurl: https://daily.dev/tos/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: this Agreement constitutes the legally binding agreement between you (either an individual or an entity)\n    and the Company\nrestricted_uses:\n- summary: No groups for illegal promotion\n  text: You may not create any Group in order to promote illegal activities, products, or services\n- summary: No competing products via Public API\n  text: use the Public API, or any data returned by the Public API, to develop, operate, support,\
  \ or contribute\n    to a Competing Product\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: you are at least 18 years old\n"
source_yaml_url: https://artifacts.apis.io/daily-dev/eligibility/daily-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from daily-dev's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Developer Tools
- NewsAggregator
- Artificial Intelligence
- Community
---
