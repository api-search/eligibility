---
api_specs:
- filename: wahoo-permissions-api-openapi.yml
  format: yaml
  label: Wahoo Fitness Permissions API
  slug: wahoo-permissions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wahoo/openapi/wahoo-permissions-api-openapi.yml
- filename: wahoo-plans-api-openapi.yml
  format: yaml
  label: Wahoo Fitness Plans API
  slug: wahoo-plans-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wahoo/openapi/wahoo-plans-api-openapi.yml
- filename: wahoo-power-zones-api-openapi.yml
  format: yaml
  label: Wahoo Fitness Power Zones API
  slug: wahoo-power-zones-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wahoo/openapi/wahoo-power-zones-api-openapi.yml
- filename: wahoo-routes-api-openapi.yml
  format: yaml
  label: Wahoo Fitness Routes API
  slug: wahoo-routes-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wahoo/openapi/wahoo-routes-api-openapi.yml
- filename: wahoo-users-api-openapi.yml
  format: yaml
  label: Wahoo Fitness Users API
  slug: wahoo-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wahoo/openapi/wahoo-users-api-openapi.yml
- filename: wahoo-workout-file-uploads-api-openapi.yml
  format: yaml
  label: Wahoo Fitness Workout File Uploads API
  slug: wahoo-workout-file-uploads-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wahoo/openapi/wahoo-workout-file-uploads-api-openapi.yml
- filename: wahoo-workout-summaries-api-openapi.yml
  format: yaml
  label: Wahoo Fitness Workout Summaries API
  slug: wahoo-workout-summaries-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wahoo/openapi/wahoo-workout-summaries-api-openapi.yml
- filename: wahoo-workouts-api-openapi.yml
  format: yaml
  label: Wahoo Fitness Workouts API
  slug: wahoo-workouts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/wahoo/openapi/wahoo-workouts-api-openapi.yml
claim_count: 7
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you are a sole proprietor, that you are at least 18 years of age.
    type: individual
  - text: If you are entering into this Agreement on behalf of an entity, that you have the legal authority to bind that entity to this Agreement.
    type: business
  - text: If you are part of any agency, department or other entity of the U.S. Government, the use, duplication, reproduction, release, modification, disclosure or transfer of the Wahoo API Materials are restricted
    type: government
  minimum_age:
    text: If you are a sole proprietor, that you are at least 18 years of age.
    value: '18'
  restricted_uses:
  - summary: No use competing with Wahoo
    text: You may not use the Wahoo API Materials in any manner that is competitive to Wahoo or the Wahoo Platform
  - summary: No use for unlawful or harmful content
    text: You may not use the Wahoo API Materials to distribute any virus, spyware, adware, malware, or other harmful or malicious content.
  verification:
    approval_required: true
    kyb: null
    kyc: null
    text: Once your registration to use the Wahoo API Materials is approved, you will receive a unique API Token
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: Wahoo Fitness
provenance_date: '2026-11-10'
provider_name: Wahoo Fitness
provider_slug: wahoo
slug: wahoo-eligibility
source_date: '2026-11-10'
source_filename: wahoo-eligibility.yml
source_heading: Eligibility
source_page: https://www.wahoofitness.com/wahoo-api-agreement
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Wahoo Fitness\naid: wahoo\nurl: https://www.wahoofitness.com/wahoo-api-agreement\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: If you are a sole proprietor, that you are at least 18 years of age.\n- type: business\n  text: If you are entering into this Agreement on behalf of an entity, that you have the legal authority to bind\n    that entity to this Agreement.\n- type: government\n  text: If you are part of any agency, department or other entity of the U.S. Government, the use, duplication,\n    reproduction, release, modification,\
  \ disclosure or transfer of the Wahoo API Materials are restricted\nrestricted_uses:\n- summary: No use competing with Wahoo\n  text: You may not use the Wahoo API Materials in any manner that is competitive to Wahoo or the Wahoo Platform\n- summary: No use for unlawful or harmful content\n  text: You may not use the Wahoo API Materials to distribute any virus, spyware, adware, malware, or other harmful\n    or malicious content.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: true\n  text: Once your registration to use the Wahoo API Materials is approved, you will receive a unique API Token\nminimum_age:\n  value: '18'\n  text: If you are a sole proprietor, that you are at least 18 years of age.\n"
source_yaml_url: https://artifacts.apis.io/wahoo/eligibility/wahoo-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 7 quoted statements, read from Wahoo Fitness's own page on 2026-11-10.
synthetic: false
tags:
- Fitness
- Cycling
- Endurance Training
- Bike Computers
- Smart Trainers
- Indoor Cycling
- Heart Rate
- Power Meters
- GPS
- Wearables
- Hardware
- FIT Files
- Webhook
- OAuth
- Authentication
---
