---
api_specs:
- filename: fatsecret-exercise-diary-api-openapi.yml
  format: yaml
  label: fatsecret Exercise Diary API
  slug: fatsecret-exercise-diary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-exercise-diary-api-openapi.yml
- filename: fatsecret-food-diary-api-openapi.yml
  format: yaml
  label: fatsecret Food Diary API
  slug: fatsecret-food-diary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-food-diary-api-openapi.yml
- filename: fatsecret-foods-api-openapi.yml
  format: yaml
  label: fatsecret Foods API
  slug: fatsecret-foods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-foods-api-openapi.yml
- filename: fatsecret-image-recognition-api-openapi.yml
  format: yaml
  label: fatsecret Image Recognition API
  slug: fatsecret-image-recognition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-image-recognition-api-openapi.yml
- filename: fatsecret-natural-language-processing-api-openapi.yml
  format: yaml
  label: fatsecret Natural Language Processing API
  slug: fatsecret-natural-language-processing-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-natural-language-processing-api-openapi.yml
- filename: fatsecret-profile-foods-api-openapi.yml
  format: yaml
  label: fatsecret Profile Foods API
  slug: fatsecret-profile-foods-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-profile-foods-api-openapi.yml
- filename: fatsecret-profile-meals-api-openapi.yml
  format: yaml
  label: fatsecret Profile Meals API
  slug: fatsecret-profile-meals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-profile-meals-api-openapi.yml
- filename: fatsecret-recipes-api-openapi.yml
  format: yaml
  label: fatsecret Recipes API
  slug: fatsecret-recipes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-recipes-api-openapi.yml
- filename: fatsecret-reference-api-openapi.yml
  format: yaml
  label: fatsecret Reference API
  slug: fatsecret-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-reference-api-openapi.yml
- filename: fatsecret-weight-tracking-api-openapi.yml
  format: yaml
  label: fatsecret Weight Tracking API
  slug: fatsecret-weight-tracking-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fatsecret/openapi/fatsecret-weight-tracking-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: you and, if applicable, the company your represent (collectively "you")
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Diet, nutrition or health advice
    text: use the fatsecret Platform API to provide diet, nutrition or health advice, guidance or diagnosis
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
name: fatsecret
provenance_date: '2026-11-09'
provider_name: fatsecret
provider_slug: fatsecret
slug: fatsecret-eligibility
source_date: '2026-11-09'
source_filename: fatsecret-eligibility.yml
source_heading: Eligibility
source_page: https://platform.fatsecret.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: fatsecret\naid: fatsecret\nurl: https://platform.fatsecret.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: you and, if applicable, the company your represent (collectively \"you\")\nrestricted_uses:\n- summary: Diet, nutrition or health advice\n  text: use the fatsecret Platform API to provide diet, nutrition or health advice, guidance or diagnosis\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fatsecret/eligibility/fatsecret-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from fatsecret's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Barcode Scanning
- Calories
- Diets
- Image Recognition
- Natural Language Processing
- Exercise
- Fitness
- Food Diary
- Health
- Macronutrients
- Nutrition
- Recipes
- Weight Tracking
- Food and Beverage
---
