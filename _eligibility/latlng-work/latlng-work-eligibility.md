---
api_specs:
- filename: latlng-work-geocoding-api-openapi.yml
  format: yaml
  label: latlng-work Geocoding API
  slug: latlng-work-geocoding-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latlng-work/openapi/latlng-work-geocoding-api-openapi.yml
- filename: latlng-work-places-api-openapi.yml
  format: yaml
  label: latlng-work Places API
  slug: latlng-work-places-api
  spec_type: OpenAPI
  url: https://artifacts.apis.io/latlng-work/openapi/latlng-work-places-api-openapi.yml
claim_count: 4
description: ''
doc:
  countries:
    excluded: []
    served: []
    text: null
  entity_types:
  - text: 'Individuals: A single natural person, regardless of the number of email addresses or devices they possess'
    type: individual
  - text: 'Businesses: A single company, corporation, LLC, partnership, or any other business organization, including all subsidiaries, divisions, and affiliates'
    type: business
  - text: 'Organizations: Non-profits, government agencies, educational institutions, and any other organizational entities'
    type: nonprofit
  minimum_age:
    text: null
    value: null
  restricted_uses:
  - summary: Illegal purposes
    text: You must not use the API for any illegal purposes
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
name: latlng-work
provenance_date: '2026-11-09'
provider_name: latlng-work
provider_slug: latlng-work
slug: latlng-work-eligibility
source_date: '2026-11-09'
source_filename: latlng-work-eligibility.yml
source_heading: Eligibility
source_page: https://www.latlng.work/terms
source_url: ''
source_yaml: "# Read from the provider's own page by engine/business/harvest-business.py. Every `text` is quoted verbatim from `url` (or the row's `source`); `unstated` means the page did not say.\neligibility: 0.1.0\nprovider: latlng-work\naid: latlng-work\nurl: https://www.latlng.work/terms\nsource_date: '2026-11-09'\nx-apis-io-derivation:\n  synthetic: false\n  method: harvested\n  read: '2026-11-09'\n  tool: engine/business/harvest-business.py\n  model: claude-haiku-5-5\ncountries:\n  served: []\n  excluded: []\n  text: null\nentity_types:\n- type: individual\n  text: 'Individuals: A single natural person, regardless of the number of email addresses or devices they possess'\n- type: business\n  text: 'Businesses: A single company, corporation, LLC, partnership, or any other business organization, including\n    all subsidiaries, divisions, and affiliates'\n- type: nonprofit\n  text: 'Organizations: Non-profits, government agencies, educational institutions, and any other organizational\n\
  \    entities'\nrestricted_uses:\n- summary: Illegal purposes\n  text: You must not use the API for any illegal purposes\nverification:\n  kyc: null\n  kyb: null\n  approval_required: null\n  text: null\nminimum_age:\n  value: null\n  text: null\n"
source_yaml_url: https://artifacts.apis.io/latlng-work/eligibility/latlng-work-eligibility.yml
stated_fields:
- entity_types
- restricted_uses
summary_line: 4 quoted statements, read from latlng-work's own page on 2026-11-09.
synthetic: false
tags:
- Company
- Geocoding
- Mapping
- Location
---
