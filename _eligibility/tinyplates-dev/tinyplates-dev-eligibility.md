---
api_specs:
- filename: tinyplates-dev-health-api-openapi.yml
  format: yaml
  label: tinyplates-dev Health API
  slug: tinyplates-dev-health-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-health-api-openapi.yml
- filename: tinyplates-dev-ingredients-api-openapi.yml
  format: yaml
  label: tinyplates-dev Ingredients API
  slug: tinyplates-dev-ingredients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-ingredients-api-openapi.yml
- filename: tinyplates-dev-pantry-api-openapi.yml
  format: yaml
  label: tinyplates-dev Pantry API
  slug: tinyplates-dev-pantry-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-pantry-api-openapi.yml
- filename: tinyplates-dev-popular-api-openapi.yml
  format: yaml
  label: tinyplates-dev Popular API
  slug: tinyplates-dev-popular-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-popular-api-openapi.yml
- filename: tinyplates-dev-recipes-api-openapi.yml
  format: yaml
  label: tinyplates-dev Recipes API
  slug: tinyplates-dev-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-recipes-api-openapi.yml
- filename: tinyplates-dev-root-api-openapi.yml
  format: yaml
  label: tinyplates-dev Root API
  slug: tinyplates-dev-root-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-root-api-openapi.yml
- filename: tinyplates-dev-search-api-openapi.yml
  format: yaml
  label: tinyplates-dev Search API
  slug: tinyplates-dev-search-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-search-api-openapi.yml
- filename: tinyplates-dev-shoppinglist-api-openapi.yml
  format: yaml
  label: tinyplates-dev Shopping List API
  slug: tinyplates-dev-shoppinglist-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-shoppinglist-api-openapi.yml
- filename: tinyplates-dev-status-api-openapi.yml
  format: yaml
  label: tinyplates-dev Status API
  slug: tinyplates-dev-status-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-status-api-openapi.yml
- filename: tinyplates-dev-substitutions-api-openapi.yml
  format: yaml
  label: tinyplates-dev Substitutions API
  slug: tinyplates-dev-substitutions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/tinyplates-dev/openapi/tinyplates-dev-substitutions-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: One account per person or organisation.
    type: individual
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: use it for anything unlawful
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You need an account to get an API key.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: tinyplates-dev
provenance_date: '2026-11-10'
provider_name: tinyplates-dev
provider_slug: tinyplates-dev
slug: tinyplates-dev-eligibility
source_date: '2026-11-10'
source_filename: tinyplates-dev-eligibility.yml
source_heading: Eligibility
source_page: https://www.tinyplates.dev/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: tinyplates-dev\naid: tinyplates-dev\nurl: https://www.tinyplates.dev/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: One account per person or organisation.\nrestricted_uses:\n- summary: Unlawful use\n  text: use it for anything unlawful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: You need an account to get an API key.\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/tinyplates-dev/eligibility/tinyplates-dev-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 3 quoted statements, read from tinyplates-dev's own page on 2026-11-10.
synthetic: false
tags:
- Food
- Recipes
- Search
- Developers
---
