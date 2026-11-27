---
api_specs:
- filename: calorie-ninjas-imagetextnutrition-api-openapi.yml
  format: yaml
  label: CalorieNinjas Imagetextnutrition API
  slug: calorie-ninjas-imagetextnutrition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calorie-ninjas/openapi/calorie-ninjas-imagetextnutrition-api-openapi.yml
- filename: calorie-ninjas-nutrition-api-openapi.yml
  format: yaml
  label: CalorieNinjas Nutrition API
  slug: calorie-ninjas-nutrition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calorie-ninjas/openapi/calorie-ninjas-nutrition-api-openapi.yml
- filename: calorie-ninjas-recipe-api-openapi.yml
  format: yaml
  label: CalorieNinjas Recipe API
  slug: calorie-ninjas-recipe-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/calorie-ninjas/openapi/calorie-ninjas-recipe-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: The information provided on the Site is not intended for distribution to or use by any person or entity in any jurisdiction or country where such distribution or use would be contrary to law or regulation
  entity_types:
  - text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted to use or register for the Site.
    type: individual
  - text: these Terms of Use constitute a legally binding agreement made between you, whether personally or on behalf of an entity
    type: business
  minimum_age:
    text: The Site is intended for users who are at least 18 years old.
    value: '18'
  restricted_uses:
  - summary: Automated access
    text: you will not access the Site through automated or non-human means, whether through a bot, script or otherwise
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
name: CalorieNinjas
provenance_date: '2026-11-09'
provider_name: CalorieNinjas
provider_slug: calorie-ninjas
slug: calorie-ninjas-eligibility
source_date: '2026-11-09'
source_filename: calorie-ninjas-eligibility.yml
source_heading: Eligibility
source_page: https://calorieninjas.com/tos
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: CalorieNinjas\naid: calorie-ninjas\nurl: https://calorieninjas.com/tos\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: The information provided on the Site is not intended for distribution to or use by any person or entity\n    in any jurisdiction or country where such distribution or use would be contrary to law or regulation\nentity_types:\n- type: individual\n  text: The Site is intended for users who are at least 18 years old. Persons under the age of 18 are not permitted\n    to use or register for the Site.\n- type: business\n  text: these Terms of Use constitute a legally\
  \ binding agreement made between you, whether personally or on behalf\n    of an entity\nrestricted_uses:\n- summary: Automated access\n  text: you will not access the Site through automated or non-human means, whether through a bot, script or otherwise\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: The Site is intended for users who are at least 18 years old.\n"
source_yaml_url: https://artifacts.apis.io/calorie-ninjas/eligibility/calorie-ninjas-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- minimum_age
summary_line: 5 quoted statements, read from CalorieNinjas's own page on 2026-11-09.
synthetic: false
tags:
- Beverages
- Food
- Image Recognition
- Nutrition
- Recipes
---
