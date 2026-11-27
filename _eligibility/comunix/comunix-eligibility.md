---
api_specs:
- filename: comunix-comunix-api-api-openapi.yml
  format: yaml
  label: Comunix Comunix API
  slug: comunix-comunix-api-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comunix/openapi/comunix-comunix-api-api-openapi.yml
- filename: comunix-incidents-api-openapi.yml
  format: yaml
  label: Comunix Incidents API
  slug: comunix-incidents-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comunix/openapi/comunix-incidents-api-openapi.yml
- filename: comunix-register-api-openapi.yml
  format: yaml
  label: Comunix Register API
  slug: comunix-register-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comunix/openapi/comunix-register-api-openapi.yml
- filename: comunix-sunshine-api-openapi.yml
  format: yaml
  label: Comunix Sunshine API
  slug: comunix-sunshine-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comunix/openapi/comunix-sunshine-api-openapi.yml
- filename: comunix-tickets-api-openapi.yml
  format: yaml
  label: Comunix Tickets API
  slug: comunix-tickets-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comunix/openapi/comunix-tickets-api-openapi.yml
- filename: comunix-user-profiles-api-openapi.yml
  format: yaml
  label: Comunix User Profiles API
  slug: comunix-user-profiles-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comunix/openapi/comunix-user-profiles-api-openapi.yml
- filename: comunix-users-api-openapi.yml
  format: yaml
  label: Comunix Users API
  slug: comunix-users-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/comunix/openapi/comunix-users-api-openapi.yml
claim_count: 2
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  minimum_age:
    text: You are not allowed to use the Services if you are under 16 years of age
    value: '16'
  restricted_uses:
  - summary: Use by minors
    text: You are not allowed to use the Services if you are under 16 years of age (or the applicable age limitation under which you are not allowed to use any of our services according to the applicable law in your territory).
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
name: Comunix
provenance_date: '2026-11-09'
provider_name: Comunix
provider_slug: comunix
slug: comunix-eligibility
source_date: '2026-11-09'
source_filename: comunix-eligibility.yml
source_heading: Eligibility
source_page: https://www.getcomunix.com/terms-of-use
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Comunix\naid: comunix\nurl: https://www.getcomunix.com/terms-of-use\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types: []\nrestricted_uses:\n- summary: Use by minors\n  text: You are not allowed to use the Services if you are under 16 years of age (or the applicable age limitation\n    under which you are not allowed to use any of our services according to the applicable law in your territory).\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: '16'\n  text: You are not allowed to use the Services if you are\
  \ under 16 years of age\n"
source_yaml_url: https://artifacts.apis.io/comunix/eligibility/comunix-eligibility.yml
stated_fields:
- restricted_uses
- minimum_age
summary_line: 2 quoted statements, read from Comunix's own page on 2026-11-09.
synthetic: false
tags:
- Gaming
- Social
- Live
- Video Chat
- Poker
---
