---
api_specs:
- filename: food-and-drug-administration-animal-veterinary-api-openapi.yml
  format: yaml
  label: Food and Drug Administration Animal & Veterinary API
  slug: food-and-drug-administration-animal-veterinary-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-and-drug-administration/openapi/food-and-drug-administration-animal-veterinary-api-openapi.yml
- filename: food-and-drug-administration-device-api-openapi.yml
  format: yaml
  label: Food and Drug Administration Device API
  slug: food-and-drug-administration-device-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-and-drug-administration/openapi/food-and-drug-administration-device-api-openapi.yml
- filename: food-and-drug-administration-drug-api-openapi.yml
  format: yaml
  label: Food and Drug Administration Drug API
  slug: food-and-drug-administration-drug-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-and-drug-administration/openapi/food-and-drug-administration-drug-api-openapi.yml
- filename: food-and-drug-administration-food-api-openapi.yml
  format: yaml
  label: Food and Drug Administration Food API
  slug: food-and-drug-administration-food-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-and-drug-administration/openapi/food-and-drug-administration-food-api-openapi.yml
- filename: food-and-drug-administration-other-api-openapi.yml
  format: yaml
  label: Food and Drug Administration Other API
  slug: food-and-drug-administration-other-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-and-drug-administration/openapi/food-and-drug-administration-other-api-openapi.yml
- filename: food-and-drug-administration-tobacco-api-openapi.yml
  format: yaml
  label: Food and Drug Administration Tobacco API
  slug: food-and-drug-administration-tobacco-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/food-and-drug-administration/openapi/food-and-drug-administration-tobacco-api-openapi.yml
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
  - summary: Use violating FDA or Federal policy or law
    text: FDA reserves the right (though not the obligation) to refuse to provide openFDA to you if it is FDA’s opinion that use violates any FDA or Federal policy or law.
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
name: Food and Drug Administration
provenance_date: '2026-11-09'
provider_name: Food and Drug Administration
provider_slug: food-and-drug-administration
slug: food-and-drug-administration-eligibility
source_date: '2026-11-09'
source_filename: food-and-drug-administration-eligibility.yml
source_heading: Eligibility
source_page: https://open.fda.gov/terms/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Food and Drug Administration\naid: food-and-drug-administration\nurl: https://open.fda.gov/terms/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use violating FDA or Federal policy or law\n  text: FDA reserves the right (though not the obligation) to refuse to provide openFDA to you if it is FDA’s opinion\n    that use violates any FDA or Federal policy or law.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/food-and-drug-administration/eligibility/food-and-drug-administration-eligibility.yml
stated_fields:
- restricted_uses
summary_line: 1 quoted statement, read from Food and Drug Administration's own page on 2026-11-09.
synthetic: false
tags:
- Drugs
- Devices
- Federal Government
- Food Safety
- Public Data
- Recalls
- Adverse Events
---
