---
api_specs:
- filename: animalchecklist-com-account-api-openapi.yml
  format: yaml
  label: animalchecklist-com Account API
  slug: animalchecklist-com-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-account-api-openapi.yml
- filename: animalchecklist-com-catalogue-api-openapi.yml
  format: yaml
  label: animalchecklist-com Catalogue API
  slug: animalchecklist-com-catalogue-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-catalogue-api-openapi.yml
- filename: animalchecklist-com-diagnostics-api-openapi.yml
  format: yaml
  label: animalchecklist-com Diagnostics API
  slug: animalchecklist-com-diagnostics-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-diagnostics-api-openapi.yml
- filename: animalchecklist-com-leaderboard-api-openapi.yml
  format: yaml
  label: animalchecklist-com Leaderboard API
  slug: animalchecklist-com-leaderboard-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-leaderboard-api-openapi.yml
- filename: animalchecklist-com-quiz-api-openapi.yml
  format: yaml
  label: animalchecklist-com Quiz API
  slug: animalchecklist-com-quiz-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-quiz-api-openapi.yml
- filename: animalchecklist-com-recognition-api-openapi.yml
  format: yaml
  label: animalchecklist-com Recognition API
  slug: animalchecklist-com-recognition-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-recognition-api-openapi.yml
- filename: animalchecklist-com-sightings-api-openapi.yml
  format: yaml
  label: animalchecklist-com Sightings API
  slug: animalchecklist-com-sightings-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/animalchecklist-com/openapi/animalchecklist-com-sightings-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You need to be at least 16 years old to create an account. You need to be 18 or have the consent of your legal guardian to buy a paid plan.
    type: individual
  minimum_age:
    text: You need to be at least 16 years old to create an account.
    value: '16'
  restricted_uses:
  - summary: No medical or safety reliance
    text: Do not rely on the app for medical, veterinary or safety decisions, for example for animal bites, poisonous animals or wildlife contact.
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
name: animalchecklist-com
provenance_date: '2026-11-09'
provider_name: animalchecklist-com
provider_slug: animalchecklist-com
slug: animalchecklist-com-eligibility
source_date: '2026-11-09'
source_filename: animalchecklist-com-eligibility.yml
source_heading: Eligibility
source_page: https://animalchecklist.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: animalchecklist-com\naid: animalchecklist-com\nurl: https://animalchecklist.com/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You need to be at least 16 years old to create an account. You need to be 18 or have the consent of your\n    legal guardian to buy a paid plan.\nrestricted_uses:\n- summary: No medical or safety reliance\n  text: Do not rely on the app for medical, veterinary or safety decisions, for example for animal bites, poisonous\n    animals or wildlife contact.\nverification:\n  kyc: null\n  kyb: null\n  approval_required:\
  \ null\n  text: null\nminimum_age:\n  value: '16'\n  text: You need to be at least 16 years old to create an account.\n"
source_yaml_url: https://artifacts.apis.io/animalchecklist-com/eligibility/animalchecklist-com-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from animalchecklist-com's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Animals
- Checklist
- Mobile App
- Free
---
