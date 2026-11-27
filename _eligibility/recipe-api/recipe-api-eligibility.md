---
api_specs:
- filename: recipe-api-discovery-api-openapi.yml
  format: yaml
  label: Recipe API Discovery API
  slug: recipe-api-discovery-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-discovery-api-openapi.yml
- filename: recipe-api-image-generation-api-openapi.yml
  format: yaml
  label: Recipe API Image Generation API
  slug: recipe-api-image-generation-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-image-generation-api-openapi.yml
- filename: recipe-api-ingredients-api-openapi.yml
  format: yaml
  label: Recipe API Ingredients API
  slug: recipe-api-ingredients-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-ingredients-api-openapi.yml
- filename: recipe-api-public-api-openapi.yml
  format: yaml
  label: Recipe API Public API
  slug: recipe-api-public-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-public-api-openapi.yml
- filename: recipe-api-recipes-api-openapi.yml
  format: yaml
  label: Recipe API Recipes API
  slug: recipe-api-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/recipe-api/openapi/recipe-api-recipes-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 years old or have the legal authority to enter into these Terms on behalf of your organization.
    type: individual
  - text: Ensure any employee, contractor, affiliate, or partner access is authorized by us and remains under your approved use case
    type: business
  minimum_age:
    text: You must be at least 18 years old or have the legal authority to enter into these Terms on behalf of your organization.
    value: '18'
  restricted_uses:
  - summary: Personal plan non-commercial only
    text: Personal is limited to personal, non-commercial use.
  - summary: Evaluation not for production
    text: Commercial and production applications must use Developer or a higher commercial plan.
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
name: Recipe API
provenance_date: '2026-11-10'
provider_name: Recipe API
provider_slug: recipe-api
slug: recipe-api-eligibility
source_date: '2026-11-10'
source_filename: recipe-api-eligibility.yml
source_heading: Eligibility
source_page: https://recipe-api.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Recipe API\naid: recipe-api\nurl: https://recipe-api.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 years old or have the legal authority to enter into these Terms on behalf of your\n    organization.\n- type: business\n  text: Ensure any employee, contractor, affiliate, or partner access is authorized by us and remains under your\n    approved use case\nrestricted_uses:\n- summary: Personal plan non-commercial only\n  text: Personal is limited to personal, non-commercial use.\n- summary: Evaluation\
  \ not for production\n  text: Commercial and production applications must use Developer or a higher commercial plan.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old or have the legal authority to enter into these Terms on behalf of your\n    organization.\n"
source_yaml_url: https://artifacts.apis.io/recipe-api/eligibility/recipe-api-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from Recipe API's own page on 2026-11-10.
synthetic: false
tags:
- Recipes
- Food
- Nutrition
- Ingredients
- Data
- Generative AI
- MCP
- Agents
---
