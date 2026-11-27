---
api_specs:
- filename: food-info-recipesapi-api-openapi.yml
  format: yaml
  label: Food Info Recipes API
  slug: food-info-recipesapi-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-info/openapi/food-info-recipesapi-api-openapi.yml
- filename: food-info-api-v1-api-openapi.yml
  format: yaml
  label: Food Info api v1 API
  slug: food-info-api-v1-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-info/openapi/food-info-api-v1-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a business customer (i.e. acting in the course of your trade, business, craft or profession, including any Practitioner-tier customer using Food Info in their practice), our total aggregate liability is capped at £50.
    type: business
  minimum_age:
    text: Paid plans, AI credit packs and Practitioner-tier access require you to be 18 or older
    value: '18'
  restricted_uses:
  - summary: Practitioner clinical-use restriction
    text: You will not use Food Info as your sole or primary clinical-decision- support tool.
  - summary: Not medical advice or device use
    text: it must not be used as the sole or primary basis for any clinical decision.
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
name: Food Info
provenance_date: '2026-11-09'
provider_name: Food Info
provider_slug: food-info
slug: food-info-eligibility
source_date: '2026-11-09'
source_filename: food-info-eligibility.yml
source_heading: Eligibility
source_page: https://food-info.org/terms-conditions
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Food Info\naid: food-info\nurl: https://food-info.org/terms-conditions\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you are a business customer (i.e. acting in the course of your trade, business, craft or profession,\n    including any Practitioner-tier customer using Food Info in their practice), our total aggregate liability is\n    capped at £50.\nrestricted_uses:\n- summary: Practitioner clinical-use restriction\n  text: You will not use Food Info as your sole or primary clinical-decision- support tool.\n- summary: Not medical\
  \ advice or device use\n  text: it must not be used as the sole or primary basis for any clinical decision.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '18'\n  text: Paid plans, AI credit packs and Practitioner-tier access require you to be 18 or older\n"
source_yaml_url: https://artifacts.apis.io/food-info/eligibility/food-info-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 4 quoted statements, read from Food Info's own page on 2026-11-09.
synthetic: false
tags:
- Nutrition
- Food
- food-composition
- Nutrients
- Data
- Open Data
- Dietetics
- Recipes
- Health
- Research
---
