---
api_specs:
- filename: transcapi-airports-api-openapi.yml
  format: yaml
  label: TransCAPI Airports API
  slug: transcapi-airports-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-airports-api-openapi.yml
- filename: transcapi-alerts-api-openapi.yml
  format: yaml
  label: TransCAPI Alerts API
  slug: transcapi-alerts-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-alerts-api-openapi.yml
- filename: transcapi-bus-api-openapi.yml
  format: yaml
  label: TransCAPI Bus API
  slug: transcapi-bus-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-bus-api-openapi.yml
- filename: transcapi-disruptions-api-openapi.yml
  format: yaml
  label: TransCAPI Disruptions API
  slug: transcapi-disruptions-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-disruptions-api-openapi.yml
- filename: transcapi-journey-api-openapi.yml
  format: yaml
  label: TransCAPI Journey API
  slug: transcapi-journey-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-journey-api-openapi.yml
- filename: transcapi-places-api-openapi.yml
  format: yaml
  label: TransCAPI Places API
  slug: transcapi-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-places-api-openapi.yml
- filename: transcapi-rail-api-openapi.yml
  format: yaml
  label: TransCAPI Rail API
  slug: transcapi-rail-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/transcapi/openapi/transcapi-rail-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You need an account, with an email address you can receive at, to get an API key.
    type: individual
  - text: If you use TransCAPI for an organisation, you agree on its behalf.
    type: business
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Unlawful use
    text: use the service for anything unlawful
  verification:
    approval_required: false
    kyb: null
    kyc: null
    text: Keys work once the address is confirmed. One free account per person or organisation.
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: TransCAPI
provenance_date: '2026-11-10'
provider_name: TransCAPI
provider_slug: transcapi
slug: transcapi-eligibility
source_date: '2026-11-10'
source_filename: transcapi-eligibility.yml
source_heading: Eligibility
source_page: https://www.transcapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: TransCAPI\naid: transcapi\nurl: https://www.transcapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You need an account, with an email address you can receive at, to get an API key.\n- type: business\n  text: If you use TransCAPI for an organisation, you agree on its behalf.\nrestricted_uses:\n- summary: Unlawful use\n  text: use the service for anything unlawful\nverification:\n  kyc: null\n  kyb: null\n  approval_required: false\n  text: Keys work once the address is confirmed. One free account per person or organisation.\n\
  minimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/transcapi/eligibility/transcapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
summary_line: 4 quoted statements, read from TransCAPI's own page on 2026-11-10.
synthetic: false
tags:
- Company
- Transport
- United Kingdom
- Ireland
---
