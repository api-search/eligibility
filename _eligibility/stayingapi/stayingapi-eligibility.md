---
api_specs:
- filename: stayingapi-account-api-openapi.yml
  format: yaml
  label: StayingAPI Account API
  slug: stayingapi-account-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stayingapi/openapi/stayingapi-account-api-openapi.yml
- filename: stayingapi-data-api-openapi.yml
  format: yaml
  label: StayingAPI Data API
  slug: stayingapi-data-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stayingapi/openapi/stayingapi-data-api-openapi.yml
- filename: stayingapi-jobs-api-openapi.yml
  format: yaml
  label: StayingAPI Jobs API
  slug: stayingapi-jobs-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/stayingapi/openapi/stayingapi-jobs-api-openapi.yml
claim_count: 5
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: You must be at least 18 (or the age of majority where you live) and able to form a binding contract.
    type: individual
  - text: between you (and, if you act for an organization, that organization)
    type: business
  minimum_age:
    text: You must be at least 18 (or the age of majority where you live)
    value: '18'
  restricted_uses:
  - summary: Sanctioned parties and territories
    text: use the Service on behalf of a sanctioned party or in a sanctioned territory.
  verification:
    approval_required: null
    kyb: null
    kyc: null
    text: You must provide accurate account information and verify your email
excluded_countries: []
layer: eligibility
layer_version: 0.1.0
layout: eligibility
method: harvested
model: claude-haiku-5-5
name: StayingAPI
provenance_date: '2026-11-10'
provider_name: StayingAPI
provider_slug: stayingapi
slug: stayingapi-eligibility
source_date: '2026-11-10'
source_filename: stayingapi-eligibility.yml
source_heading: Eligibility
source_page: https://stayingapi.com/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: StayingAPI\naid: stayingapi\nurl: https://stayingapi.com/terms\nsource_date: '2026-11-10'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-10'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: You must be at least 18 (or the age of majority where you live) and able to form a binding contract.\n- type: business\n  text: between you (and, if you act for an organization, that organization)\nrestricted_uses:\n- summary: Sanctioned parties and territories\n  text: use the Service on behalf of a sanctioned party or in a sanctioned territory.\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text:\
  \ You must provide accurate account information and verify your email\nminimum_age:\n  value: '18'\n  text: You must be at least 18 (or the age of majority where you live)\n"
source_yaml_url: https://artifacts.apis.io/stayingapi/eligibility/stayingapi-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
- verification
- minimum_age
summary_line: 5 quoted statements, read from StayingAPI's own page on 2026-11-10.
synthetic: false
tags:
- Travel
- Hospitality
- accommodation-data
- hotel-api
- Vacation Rentals
- Short-Term Rental
- Airbnb
- Booking.com
- Vrbo
- google-hotels
- cross-ota-price-comparison
- Availability
- Reviews
- REST
- MCP
- Agent-Native
- OpenAPI
---
