---
api_specs:
- filename: fitbark-activity-api-openapi.yml
  format: yaml
  label: FitBark Activity API
  slug: fitbark-activity-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-activity-api-openapi.yml
- filename: fitbark-dog-api-openapi.yml
  format: yaml
  label: FitBark Dog API
  slug: fitbark-dog-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-dog-api-openapi.yml
- filename: fitbark-goals-api-openapi.yml
  format: yaml
  label: FitBark Goals API
  slug: fitbark-goals-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-goals-api-openapi.yml
- filename: fitbark-user-api-openapi.yml
  format: yaml
  label: FitBark User API
  slug: fitbark-user-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-user-api-openapi.yml
- filename: fitbark-oauth-api-openapi.yml
  format: yaml
  label: FitBark O Auth API
  slug: fitbark-oauth-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/fitbark/openapi/fitbark-oauth-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: Rules for software developers and third parties who use our API
    type: developer
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Developer applications only
    text: You may not use the FitBark API to design anything other than Developer Applications.
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
name: FitBark
provenance_date: '2026-11-09'
provider_name: FitBark
provider_slug: fitbark
slug: fitbark-eligibility
source_date: '2026-11-09'
source_filename: fitbark-eligibility.yml
source_heading: Eligibility
source_page: https://help.fitbark.com/en/articles/6490193-api-terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: FitBark\naid: fitbark\nurl: https://help.fitbark.com/en/articles/6490193-api-terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: developer\n  text: Rules for software developers and third parties who use our API\nrestricted_uses:\n- summary: Developer applications only\n  text: You may not use the FitBark API to design anything other than Developer Applications.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/fitbark/eligibility/fitbark-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 2 quoted statements, read from FitBark's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Dogs
- Pets
- Wearables
- Activity Tracking
- Health
- IoT
- Fitness
---
