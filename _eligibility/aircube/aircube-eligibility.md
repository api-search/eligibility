---
api_specs:
- filename: aircube-aircube-api-api-openapi.yml
  format: yaml
  label: AirCube AirCube API
  slug: aircube-aircube-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircube/openapi/aircube-aircube-api-api-openapi.yml
- filename: aircube-models-api-openapi.yml
  format: yaml
  label: AirCube Models API
  slug: aircube-models-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircube/openapi/aircube-models-api-openapi.yml
- filename: aircube-qwen-image-api-openapi.yml
  format: yaml
  label: AirCube Qwen Image API
  slug: aircube-qwen-image-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aircube/openapi/aircube-qwen-image-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: You may not use the Services if you are barred from doing so under the laws of Hong Kong or any other applicable jurisdiction.
  entity_types:
  - text: You must be at least 18 years old, or the age of majority in your jurisdiction, and capable of entering into a binding contract to use the Services.
    type: individual
  minimum_age:
    text: You must be at least 18 years old, or the age of majority in your jurisdiction
    value: '18'
  restricted_uses:
  - summary: Prohibited content categories
    text: 'You must not use the Services to create, distribute, or facilitate content that: is unlawful, or that promotes or facilitates illegal activity;'
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: To use most features you must create an account, including by signing in through a third-party provider such as Google or GitHub.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: AirCube
provenance_date: '2026-11-09'
provider_name: AirCube
provider_slug: aircube
slug: aircube-eligibility
source_date: '2026-11-09'
source_filename: aircube-eligibility.yml
source_heading: Eligibility
source_page: https://aircube.ai/legal/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: AirCube\naid: aircube\nurl: https://aircube.ai/legal/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: You may not use the Services if you are barred from doing so under the laws of Hong Kong or any other applicable\n    jurisdiction.\nentity_types:\n- type: individual\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction, and capable of entering\n    into a binding contract to use the Services.\nrestricted_uses:\n- summary: Prohibited content categories\n  text: 'You must not use the Services to create, distribute, or facilitate content that:\
  \ is unlawful, or that promotes\n    or facilitates illegal activity;'\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: To use most features you must create an account, including by signing in through a third-party provider\n    such as Google or GitHub.\nminimum_age:\n  value: '18'\n  text: You must be at least 18 years old, or the age of majority in your jurisdiction\n"
source_yaml_url: https://artifacts.apis.io/aircube/eligibility/aircube-eligibility.yml
stated_fields:
- countries
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from AirCube's own page on 2026-11-09.
synthetic: false
tags:
- Artificial Intelligence
- Platform
- Media Generation
- Unified API
---
