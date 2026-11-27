---
api_specs:
- filename: aviation-edge-reference-api-openapi.yml
  format: yaml
  label: Aviation Edge Reference API
  slug: aviation-edge-reference-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviation-edge/openapi/aviation-edge-reference-api-openapi.yml
- filename: aviation-edge-satellites-api-openapi.yml
  format: yaml
  label: Aviation Edge Satellites API
  slug: aviation-edge-satellites-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviation-edge/openapi/aviation-edge-satellites-api-openapi.yml
- filename: aviation-edge-schedules-api-openapi.yml
  format: yaml
  label: Aviation Edge Schedules API
  slug: aviation-edge-schedules-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviation-edge/openapi/aviation-edge-schedules-api-openapi.yml
- filename: aviation-edge-notams-api-openapi.yml
  format: yaml
  label: Aviation Edge NOTA Ms API
  slug: aviation-edge-notams-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviation-edge/openapi/aviation-edge-notams-api-openapi.yml
- filename: aviation-edge-realtime-api-openapi.yml
  format: yaml
  label: Aviation Edge Realtime API
  slug: aviation-edge-realtime-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/aviation-edge/openapi/aviation-edge-realtime-api-openapi.yml
claim_count: 3
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: If you act on behalf of an entity, you represent and warrant that you are authorized to bind that entity.
    type: business
  minimum_age:
    text: You must be of legal age and eligible to enter into contracts in your jurisdiction.
    value: null
  restricted_uses:
  - summary: No military or defense purposes
    text: Our data and services must not be used for any military, defense, weaponry, or related intelligence purposes.
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
name: Aviation Edge
provenance_date: '2026-11-09'
provider_name: Aviation Edge
provider_slug: aviation-edge
slug: aviation-edge-eligibility
source_date: '2026-11-09'
source_filename: aviation-edge-eligibility.yml
source_heading: Eligibility
source_page: https://aviation-edge.com/api-terms-of-service/
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: Aviation Edge\naid: aviation-edge\nurl: https://aviation-edge.com/api-terms-of-service/\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: business\n  text: If you act on behalf of an entity, you represent and warrant that you are authorized to bind that entity.\nrestricted_uses:\n- summary: No military or defense purposes\n  text: Our data and services must not be used for any military, defense, weaponry, or related intelligence purposes.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text:\
  \ You must be of legal age and eligible to enter into contracts in your jurisdiction.\n"
source_yaml_url: https://artifacts.apis.io/aviation-edge/eligibility/aviation-edge-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- minimum_age
summary_line: 3 quoted statements, read from Aviation Edge's own page on 2026-11-09.
synthetic: false
tags:
- Airlines
- Airports
- Aviation
- Flight Data
- Real-Time
---
