---
api_specs:
- filename: mealdb-categories-php-api-openapi.yml
  format: yaml
  label: TheMealDB Categories.php API
  slug: mealdb-categories-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-categories-php-api-openapi.yml
- filename: mealdb-filter-php-api-openapi.yml
  format: yaml
  label: TheMealDB Filter.php API
  slug: mealdb-filter-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-filter-php-api-openapi.yml
- filename: mealdb-list-php-api-openapi.yml
  format: yaml
  label: TheMealDB List.php API
  slug: mealdb-list-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-list-php-api-openapi.yml
- filename: mealdb-lookup-php-api-openapi.yml
  format: yaml
  label: TheMealDB Lookup.php API
  slug: mealdb-lookup-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-lookup-php-api-openapi.yml
- filename: mealdb-premium-api-openapi.yml
  format: yaml
  label: TheMealDB Premium API
  slug: mealdb-premium-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-premium-api-openapi.yml
- filename: mealdb-random-php-api-openapi.yml
  format: yaml
  label: TheMealDB Random.php API
  slug: mealdb-random-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-random-php-api-openapi.yml
- filename: mealdb-search-php-api-openapi.yml
  format: yaml
  label: TheMealDB Search.php API
  slug: mealdb-search-php-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-search-php-api-openapi.yml
- filename: mealdb-discovery-api-openapi.yml
  format: yaml
  label: TheMealDB Discovery API
  slug: mealdb-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-discovery-api-openapi.yml
- filename: mealdb-filter-api-openapi.yml
  format: yaml
  label: TheMealDB Filter API
  slug: mealdb-filter-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-filter-api-openapi.yml
- filename: mealdb-lists-api-openapi.yml
  format: yaml
  label: TheMealDB Lists API
  slug: mealdb-lists-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-lists-api-openapi.yml
- filename: mealdb-lookup-api-openapi.yml
  format: yaml
  label: TheMealDB Lookup API
  slug: mealdb-lookup-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-lookup-api-openapi.yml
- filename: mealdb-search-api-openapi.yml
  format: yaml
  label: TheMealDB Search API
  slug: mealdb-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/mealdb/openapi/mealdb-search-api-openapi.yml
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
  - summary: App store publishing requires paid subscription
    text: You cannot publish apps to an appstore unless you are a paid subscriber.
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
name: TheMealDB
provenance_date: '2026-11-10'
provider_name: TheMealDB
provider_slug: mealdb
slug: mealdb-eligibility
source_date: '2026-11-10'
source_filename: mealdb-eligibility.yml
source_heading: Eligibility
source_page: https://www.themealdb.com/terms_of_use.php
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TheMealDB\naid: mealdb\nurl: https://www.themealdb.com/terms_of_use.php\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: App store publishing requires paid subscription\n  text: You cannot publish apps to an appstore unless you are a paid subscriber.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/mealdb/eligibility/mealdb-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from TheMealDB's own page on 2026-11-10.
synthetic: false
tags:
- Food
- Recipes
- Meals
- Cooking
- Ingredients
- Cuisine
- Open Data
---
